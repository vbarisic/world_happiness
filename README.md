# A deeper look into world happiness

## Overview

What makes one country happier than the other? Why are Northern Europeans ranked one of the happiest year after year, while the least happiest countries tend to be mostly in Africa? 

The World Happiness Report, published annually since 2012, measures the overall happiness of more than 150 countries based on six criteria:
social support, GDP per capita, life expectancy, freedom to make life choices, generosity, and perceptions of corruption. While happiness can, and often is, quite subjective, the Report provides an interesting glimpse into the quality of life in the surveyed countries. 

In addition to the World Happiness Report, I wanted to explore the different social factors that may correlate or contribute to happiness by examining the ten top- and bottom-ranked countries from 2015-2019. 

## Gather the data

Aside from World Happiness Reports from 2015 to 2019, additional datasets to be used in this analysis are:
  * WHO Suicide Statistics - Do lower-ranked countries have higher rates of suicide?
  * Education Attainment - Is ignorance truly bliss?
  * Religion - Does religion, or faith, provide happiness?
  * GDP per Capita - They say money can't buy you happiness, but it won't make you sad, either. Or, will it? (While already used in the     Report, GDP per capita is given as a ranking as opposed to currency)
  * Rates of Unemployment - lack of employment might indicate financial hardship, and thus lower happiness levels. Is this true?
  * Physical Activity - Are active people happier?
  
Let's find out!

But first...

## Clean the data

I was lucky enough to find already cleaned datasets for the World Happiness Report from 2015 to 2019, but I couldn't find any data for it for the years prior to 2015. Other data needed to be cleaned, and many of the datasets have some missing information, such as lack of data for particular countries or for the particular years I was analyzing, or both! 

## Challenges along the way

The lack of data for the countries and years in question is the biggest challenge of this analysis. I scoured the web in search of the most complete datasets, but ultimately some countries just do not have the information I need. The unemployment rates and physical activity datasets, for example, lacked data most, if not all, of the bottom ranked countries. There was sufficient data for the top ranked countries, but without having information on the bottom ranked countries, it was impossible to draw correlations of happiness levels with unemployment and physical activity rates.

## Tools and packages used
* Excel - for cleaning data
* Pandas - data manipulation and cleaning
* Matplotlib - data visualization
* Seaborn - data visualization
* Numpy - for obtaining Pearson coefficient correlation
* Plotly - for plotting world maps

## Project screenshots
![Alt text](/images/gdppcap_vs_happiness.png)
![Alt text](/images/suicide_rates_worldmap.png)
![Alt text](/images/relg_affiliation_least.png)
![Alt text](/images/relg_affiliation_happiest.png)
