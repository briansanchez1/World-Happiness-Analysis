# World-Happiness-Analysis
Data Science Fundaments COMP3125 Final Project 

Full report found [here](https://github.com/briansanchez1/World-Happiness-Analysis/blob/main/World%20Happiness%20Report.docx). The following is a brief summay of the project.

## Introduction	
This project explores world happiness, focusing on the factors contributing to happiness and how these factors vary across different countries and demographic groups. 

## Selection of Data
The educational data used in this study was sourced from UNESCO, a renowned international organization that specializes in promoting education, science, and culture. UNESCO offers a wide range of data related to education, including global indicators on learning outcomes, literacy rates, and educational attainment. The data was generated through extensive surveys, country reports, and collaborations with national governments and international organizations. Along with this, I used data from the World Happiness Report, a global survey that ranks countries based on subjective well-being, also known as happiness. The World Happiness Report is updated annually, with the most recent dataset being from 2024. 

##  Characteristics of data
The UNESCO and World Happiness Report datasets vary in format, size, and the parameters they contain. To deal with discrepancies in the country lists and formats between the two sources, I created two additional datasets for regional mapping. This allowed for the proper alignment of happiness data across the same regions, ensuring that no critical data was omitted. 

## Methods
I created a time series analysis to examine how global happiness levels have fluctuated over time. This approach involved calculating the annual average happiness score ("Life Ladder") for each year in the dataset and plotting this against time to observe any trends or patterns. 

In addition to time series, I examined correlations between global happiness and other factors, including region, education, and economic stability. This analysis aimed to understand the relationships between these factors and happiness levels, which can provide insights into what drives happiness.

## Results
![img1](/World-Happiness-Analysis//Graph/global_happiness_trend.png)

The analysis of happiness scores over time revealed a notable pattern. In 2007, happiness levels began at a relatively low point, followed by a gradual decline in subsequent years. However, between 2016 and 2020, happiness levels saw a sharp increase, reaching an all-time high. The rise in happiness in this period contrasts with the sharp decline in 2021 and 2022, likely due to the COVID-19 pandemic, which brought unprecedented health, social, and economic challenges to the global population.As of the most recent data in 2023, happiness levels are on the rise again, but it remains uncertain whether this upward trend will continue. 

![img2](/World-Happiness-Analysis//Graph/happiness_by_education_by_region.png)
There seems to be a slight bit of a correlation between education and happiness. The general conclusion to make from this is that the regions that report low happiness will have lower years of schooling, relative to the other regions.

![img1](/World-Happiness-Analysis//Graph/happiness_vs_economic_stability.png)
The trend we see from the data might not be extremely convincing but taking into consideration the fact that this is not the only factor that contributes to happiness, this trend is consistent with existing research. However, it is worth noting that this correlation does not necessarily imply causality. In terms of economic stability, while the correlation between a stable economy and happiness exists, political stability, environmental factors, and cultural attitudes once again all play significant roles in determining the overall well-being of a population. 

## Discussion
All these findings highlight a trend, but deeper analysis would be needed to establish causal relationships. Although regional comparisons provided a useful overview, they may have oversimplified the impact of local contexts. For example, regions like Oceania or North America were highlighted as having higher happiness levels, but this does not account for the complexities within the countries themselves. A more granular analysis at the country or city level might reveal different insights, especially in larger, more diverse countries.

## Coding
[Here](https://github.com/briansanchez1/World-Happiness-Analysis/blob/main/Codes/World%20Happiness%20Analysis.ipynb)