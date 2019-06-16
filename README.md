# INVESTIGATE_A_DataSet_DAND
This project was completed as part of the course requirements of Udacity's Data Analyst Nanodegree certification.
***
### Overview
I thought it would be interesting to see how other regions in the world have being growing in terms of Income(GDP/capita PPS infaltion adjusted) as compaired to countries in africa. Also, what trends can be observed betweeen Income and other Indicators like:

> * Income and  CO2
> * Income and Child Mortality
> * Income and Life Expectancy
> * Income and Self-Employed

**The project involved identifying the appropriate datasets to answer the research questions, justifying data selection, joining multiple datasets, data assessment and cleaning, performing EDA and drawing conclusions from the data.**
***
### Analysis
use visualization to examine the spread and centrak tendencies

Correlation and linear regression hypothesis testing

### Libraries Used

Python, Numpy, Pandas, Matplotlib, Scipy.

**I also used bqplot and ipywidgets to recreat the famous hans rosling data visualisation using the dataset i cleaned**

***
### Conclusion 
* From our first plot we observe that income per capita increased as the years went by, further investigations showed that as income per capita increased, life expectancy increased. This relationship is not linear and also not causal.

* Further studies not captured in this analysis shows that the change in life expectancy occurs at different rates for different countries and is independent of changes in income for some countries, rather attributing some of the factors responsible for increase in life expectancy in countries, especially poorer ones, to education, better technology, vaccinations etc.

* One interesting thing about this analysis is the Jitterplot and boxplot on  co2 emission by region. At face value, it showed that Oceania had the highest emission values per person, but we looked closer, and realised that according to our dataset,in 2014, Europe had more countries combined emmiting more  CO2 per person above the average levels, and Trinidad and Tobago emitted the highest levels per person. Further analysis will need to be carried out before we can ascertain causality and directionality between  CO2 emission per person and Income per capita.

* From the correlation table, as well as observing the Scatter plot, we saw that the variable "Self employed" has a strong negative correlation with income per capita, which implies that richer countries tend to have less entrepreneurs i.e people that are self employed.

* Child Mortality has a strong negative correlation with income per capita implying that richer countries lose less babies at child birth. Notice that although there is a strong correlation between the two variables, we aren't still implying causation because other lurknig variables may be the direct cause of this. i.e Countries with higher income per capita may have more medical personnel per 1000 patients, meaning such countries will be in a better position to effect safer child deliveries.

* From our last graph we can denote that for each of the five regions, child mortality is reducing.
***
### CONSIDERATION

This analysis isn't full proof because of incomplete dataset. We had to drop some records which resulted in a dataset with reduced sample size, thereby reducing the statistical power of the analysis.
