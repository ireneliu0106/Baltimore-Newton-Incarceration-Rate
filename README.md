# Baltimore-Newton-Incarceration-Rate
Comparing incarceration rate in Baltimore, MD and Newton, MA
## Background
The United States has one of the highest incarceration rate in the world. In the [article published by Prison Policy Initiative](https://www.prisonpolicy.org/blog/2020/01/16/percent-incarcerated/#:~:text=Nearly%20one%20out%20of%20every,in%20a%20prison%20or%20jail.&text=We're%20often%20asked%20what,state%20prison%20or%20local%20jail.), it estimated that around 0.7% of the US population or 698 per 100,000 people are currently imprisoned. It is essential to explore the reasons why so many people are incarcerated to create better solutions to fix the issues. We will take a look at the open data from [Opportunity Atlas](https://www.opportunityatlas.org/) and compare the incarceration rates at Baltimore, MD and Newton Center, MA in relation to parent income. A city in Massachusetts was chosen because it has one of the lowest incarceration rates in the US. It would be worthwhile to explore the relationship between parent income and incarceration rate at cities with medium-high incarceration rate and low incarceration rate to get a more wholistic view. 
## Business Question
What is the relationship between incarceration rates and parent income in Baltimore, MD and Newton Center, MA?
## Data Question -- Open Data
All the datasets were downloaded from [Opportunity Atlas](https://www.opportunityatlas.org/)
1. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p75.xlsx) contains incarceration rates in Baltimore, MD with high (75 percentile) parent income
2. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p50.xlsx) contains incarceration rates in Baltimore, MD with middle (50 percentile) parent income
3. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p25.xlsx) contains incarceration rates in Baltimore, MD with low (25 percentile) parent income
4. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p75%20(1).xlsx) contains incarceration rates in Newton Center, MA with high (75 percentile) parent income
5. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p50%20(1).xlsx) contains incarceration rates in Newton Center, MA with middle (50 percentile) parent income
6. [This dataset](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/shown_tract_jail_rP_gP_p25%20(1).xlsx) contains incarceration rates in Newton Center, MA with low (25 percentile) parent income
## Data Analysis
Here are the [Excel file](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/Incarceration%20Rate%20Analysis.xlsx) for data analysis and the [step-by-step descriptions](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/Step-by-step%20instructions%20of%20Excel%20data%20analysis) of Excel data analysis

__What is the average incarceration rate in Baltimore, MD in relation to parent income?__
![alt text](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/Baltimore%2C%20MD.png)
We can see from the graph that in Baltimore, the average incarceration rate is the highest among the tract with low parent income and the lowest among the tract with high parent income. We can conclude from this result that average incarceration rate is inversely proportional to parent income in Baltimore, MD.

__What is the average incarceration rate in Newton Center, MA in relation to parent income?__
![alt text](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/Newton%2C%20MA.png)
A similar analysis is performed in Newton Center, MA. We can also find that the average incarceration rate is the highest among the tract with low parent income and the lowest among the tract with high parent income. We draw similar conclusion from this result that average incarceration rate is inversely proportional to parent income in Newton, MA.

__How is the average incarceration rate in Baltimore, MD and compare to that of Newton Center, MA?__
![alt text](https://github.com/ireneliu0106/Baltimore-Newton-Incarceration-Rate/blob/main/Combined.png)
As shown in the combined graph, the average incarceration rate in Baltimore, MD is significantly higher than Newton Center, MA. However, regardless of the incarceration rate, the trend that low parent income tract has the highest incarceration rate still remains in both Baltimore and Newton Center. 
## Business Answer
Based on the data analysis, we can see that in both Baltimore, MD and Newton Center, MA, the average incarceration rate and parent income exhibit an inverse relationship, even though the total avergae incarceration rates in the two cities are significantly different. More in-depth data analysis can be conducted in other cities as well to see if such trend applies to most cities in the US. This analysis is important, as we can see if solutions can be taylored specifically to this finding in order to lower the incarceration rate in the US. In future studies, we can also look at additional data such as the individual/household income vs incarceration rate or parent incarceration rate vs children incarceration rate to further explore the role of parent and income play on incarceration rate. 
