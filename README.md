
# Data Interpretations & Visualization
## 21479_5




## Authors

- [@David-Adams](https://github.com/dra27013/GroupProject_Tableau)
- [@Chaewon-Kang](https://github.com/cwon-kang/khaki)
- [@Spencer-Gordon](https://github.com/SpencerGordon16/GroupProject2MIST4610.git) 
- [@Erin-ODea](https://github.com/erinodea/SQLproj2)
- [@Kenny-Johnson](https://github.com/kmj07215/4610-GP-2) 



## Dataset
This dataset combines countries' Covid-19 specs and a long list of health indicators that may relate to  Covid-19 death and infection risk.

### Dataset source
Kaggle: https://www.kaggle.com/datasets/nxpnsv/country-health-indicators 

### Dataset dimensions
This dataset has 180 rows/values representing different countries. There are 70 columns describing each country. They range from Covid-related data such as CaseGrowth (String) and first1ConfirmedCases (Date). Other country health indicators include Cardiovascular diseases % (Number) and population (Number).

### Manipulations
There were no manipulations or calculations applied to the data set as a part of the analysis. 

## Questions

### Question 1
Do pre-existing conditions such as cardiovascular diseases, HIV/respiratory diseases, and cancer affect countries' Covid growth and death rates? Are there any extraneous variables that may influence the data?

![Logo](https://github.com/cwon-kang/khaki/blob/main/question%201%20dashboard.png?raw=true)


#### Significance
It is important to analyze the effect Covid has on 'at risk' populations. As Covid disrupts respiratory and immune systems, countries with high pre-existing conditions may experience greater consequences from Covid. 
In the case that high at-risk population countries have much greater Covid growth and death rates, responsible governments must take action as needed.

#### Analysis
Within our visualizations it can be found that the EURO region has the highest average cardiovascular disease percentage. The AFRO region demonstrated the highest percentage of HIV/AIDS and Tuberculosis. Finally, the South East Asia region demonstrated the highest percentage of Respiratory Disease. While all of this data in theory could have a significant effect on death and case growth of Covid, it was found that the significance may not be as obvious. Although there wasn’t a definite correlation between other diseases and Covid rates, it is important to notice the shape of the data that the regions represent. Respiratory disease had similar averages across all regions, blotting most of the points together. HIV/AIDS showed a cluster of other regions data points followed by a large spread of the AFRO regions data points since it has the highest average population with that disease. The cardiovascular disease rates also showed a spread of data points, but in this case it primarily showed the EURO regions COVID-19 rates. All of this shows that since there is little causation between other diseases and COVID-19 death rates, countries with higher at-risk populations are just as susceptible to COVID-19 as countries with less at-risk populations.

#### Link to dataset
This question requires case and death growth data compared to the cardiovascular disease, respiratory disease, and HIV/AIDS tuberculosis percent of countries- all of which are from the country health indicators dataset.

### Question 2
Which WHO region had the highest reported new cases for a single month, and was there a single country region that was responsible for the majority of the reported new cases? 


![Logo](https://raw.githubusercontent.com/SpencerGordon16/GroupProject2MIST4610/85f49ead2dd4eee6ccb365d157d14ff24c928ebd/Q2%20-%20Final.png)

#### Significance
Typically, geographic regions have similar medical resources, cultures, and health statistics. We were curious if these similarities may account for varying Covid case numbers. 
By studying Covid by region and observing its movement, it gives more information about how Covid is spread, providing governments with information about what resources help against the spread of Covid. 
#### Analysis
These visualizations demonstrate to us that the Western Pacific Region had the convincingly largest spike in new cases, which took place at the end of 2022 and began declining at the start of 2023. We were able to dive deeper and see that China made up the vast majority of this spike in cases compared to the rest of the region. The final visualization is the rate of new cases by day. This spike occurred in December 2022, and almost 7 million new cases were reported on December 22nd. This is very interesting to see and is easily explained by the timeline of COVID-19. 2022 was the first time after the start of the pandemic that people traveled to spend time with family and loved ones around the holidays. It is interesting to see that this spike is much higher than in what we believed to be in the height of the pandemic. At this point in time, individuals were more comfortable traveling and vaccines were very widely accessible, and this explains why the number of new cases is so high.

#### Link to dataset
This question requires us to compare new cases data from the WHO dataset by regions to find the region with the highest case numbers. Analyzing the case numbers using a boxplot shows us countries in each region with outlying new case numbers. 



