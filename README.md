# PyBer Analysis

## Overview Of Analysis

When it came to the dataset provided by company Pyber, our initial analysis showed how total fare, ride count and driver count were impacted by city type (suburban, urban and rural) for the year 2019. The analysis showed evidence that urban cities had the most total number of rides and driver count while also showing the lowest average fares. Rural cities had the least number of rides and driver count and had the highest average fare. Suburban city ranged in the middle for all three categories (average fare, driver count and ride count). The data is presented in the bubble chart displayed below.
![image](https://user-images.githubusercontent.com/26393180/151722836-a323416d-cd5d-46bf-90ac-7990c92bd410.png)
After the initial report, further analysis was completed to find the weekly average fare from January 2019 through April 2019 for each city type. The analysis was completed and presented in a line graph.

## Results

The below DataFrame displays the initial calculations for the 2019 Pyber dataset as a whole. The data shows urban towns have the most total rides and drivers while also having the least average fare per ride and average fare per driver. Rural cities in 2019 had the least total rides and total drivers while also having the most average fare per ride and average fare per driver. Suburban cities scores in the middle for all categories. 
![image](https://user-images.githubusercontent.com/26393180/151722921-bc73e4eb-0c58-422f-ba9e-114364957ccf.png)

From here, the data collected from 01.01.2019 – 04.28.2019 was pulled into its own DataFrame for further analysis. The data collected was first grouped by city type, then grouped by week during the selected date range. The fare sum per week throughout the selected date range was calculated and plotted in the below line graph.
![image](https://user-images.githubusercontent.com/26393180/151722937-354810e9-20f4-48fd-9864-343bc1dd224b.png)
The data plotted in the line graph above shows there is a difference in the sum of weekly fares between the three city types: rural, suburban, and urban. Urban cities had the highest fare sum, suburban second highest fare sum and rural the least fare sum throughout the selected date range. There is no cross over between the city types and sum of fares for the selected date range. 

## Summary

Based on this analysis, there are recommendations to help address the disparities amount the city types.
* Increase the number of drivers in rural cities. The data shows that the number of rides is almost twice as high as the number of drivers. By adding more drivers to help with ride demand this may increase the total fares for this city type.
* Increase the number of drivers in suburban cities. The data shows that there is about 1/3  times more riders as there are drivers. By adding more drivers to help with ride demand this may increase the total fares for this city type.
* Increase the fare cost for both rural and suburban towns. Since there appears to be quite a demand for rides for these city types, by increasing the fare cost this will both reduce the disparities among the city types while also increase profit for Pyber. 
