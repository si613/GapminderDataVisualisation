# World Bank Data

In 2006, `Hans Rosling` gave a TED talk titled [The best stats you've ever seen](https://youtu.be/hVimVzgtD6w?si=Jthy0DcT69vJ6PtY). At the beginning of the talk, he showed an animation he made to debunk some misconceptions about today's world. <br>
Hans Rosling built this animation after testing his students on global health; he realised that they still thought that the world was divided in two:

- Western world: *low fertility rate and high life expectancy*
- Third world: *high fertility rate and low life expectancy*

## Background 
The visualisations will be modelled after the `Gapminder` visualisations, a non-profit founded by Hans Rosling along with his son and daughter-in-law that aims to make data accessible to drive positive change. <br> 
- While dealing with visualisations of indicators such as population, life expectancy, and fertility rate, we peek into the social, economic, and political driving forces that contributed to the numbers. 
- For example, across the various visualisations, we see the Sub-Saharan region lagging behind. This is a testament to the post-colonial and modern imperial forces that still operate in the continent.
- A solid example is the HIV epidemic that halted and reversed the growth of the region. While life-saving drugs were available, they were too expensive to be used even by the top-earning portion of the population. Monopolistic practises in healthcare by the big pharma, backed by favourable intellectual property regulations, affected the lives of millions of Africans for decades. More on this subject is covered in the documentary [Fire In the Blood](https://www.youtube.com/watch?v=uMsseS_Lqs0&t=1s).
- Similarly, in another example, China's rapid decline in fertility rate can be attributed to their adoption of the one-child policy.
<br> 

As the gapminder’s purpose states and as is the responsibility of people dealing with data and decision-makers, I take this opportunity to emphasize the need for sustainable progress and preventing disasters through interdisciplinary collaborations.

## Dataset Information
- **Life expectancy at birth**: The number of years a newborn would live if the patterns of mortality at the time of birth remain the same throughout his life.

- **Fertility rate**: Number of children a woman would give birth to during her childbearing years. 

- **Country population**: Total number of residents regardless of legal status or citizenship (midyear estimates)
- **Meta Data**: In this dataset, we will find Income groups and regions that different countries fall under.

There will be some differences between the original visualisation 
- **More data:**  The talk was made in 2006 with data from 1962 to 2003. We will use data from 1960 to 2016.
- **Regions:** The original visualisation has five regions. We will keep the regions from the source data (i.e. seven regions).

## Data Overview and Preprocessing
In the data preprocessing notebook file, the four datasets were explored individually, melted and merged to produce a final dataset that could be used for visualisations. The null values were removed from the dataset.
<br>
The detailed procedure is illustrated in the Jupyter Notebook files.
## Data Visualisations
Detailed observations of the visualisations are illustrated in the visualisation notebook.
1. Regional data is analysed to count the countries in each region.
2. Population trend over time was charted through line, area and bar graphs.
3. Fertility rate distribution was analysed, and its shift over time was noted.
4. The variance in life expectancy was charted across different income groups and regions.
5. Pairplot analysis was conducted for the numerical variables.
6. Gapminder visualisations inspired the population bubble chart of life expectancy and fertility rate. 
<br>

**NOTE:**
The visualisations made using Plotly Express are not visible in the GitHub preview. A PDF with all the visualisations is also attached for ease of viewing. Snapshots of the animated visuals are added.

## Challenges
The major challenge during this project was figuring out the steps involved in data preprocessing that can convert and combine the data into usable format for compelling visualisations. This hurdle was overcome by the `pd.melt()` function which helped unpivot the dataframes, after which merge and visualisations were conducted smoothly. 
