# Pyber_Analysis

## Overview of the analysis:
Pyber is a ride-sharing app used across the country. This analysis aims to improve Pyber's ride-sharing services by illustrating and describing the data divided by city types. This analysis uses Python scripts with Pandas library and Matplotlib through Jupyter Notebook. 


## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

Pyber's given data (city_data.csv & ride_data.csv) are merged by the "city" column and split into three city types. These types are Urban, Suburban, and Rural. The image of the data frame below describes the total rides, total drives, and total fares among each city type.

![Pyber_Dataframe_Summary](https://github.com/XSR700/Pyber_Analysis/blob/main/analysis/Dataframe_Symmary.PNG)

In addition, the figure displays the average fare per ride and average fare per driver for each city type. Analyzing the data frame, it is clear that urban and suburban cities generate significantly more rides than rural cities. We also see that the average fare per driver and per ride is highest among rural cities. Urban cities had more drivers than rides. Due to the competition among drivers, Urban drivers had the lowest average fare. 

The line graph below illustrates how Pyber's fare performed in each city type from January to May of 2019. The fare across Urban cities has been the highest across all dates. The highest fare prices peaked in urban cities during the end of February and the beginning of March. In fact, each city type peaked around this time with the exception of rural fare reaching the highest in April. All city types performed with steady positions across all four months. 

![Total_Fare_by_City_Type](https://github.com/XSR700/Pyber_Analysis/blob/main/analysis/total_fare_by_type.PNG)


## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

After analyzing the data and interpreting a graph we can come up with recommendations. 

According to the data frame we see that there are more drivers than rides in urban cities. This leads to drivers struggling to get passengers when competition is high. the CEO could set a campaign and encourage drivers to work in suburban or rural areas of the city and spread out the population. 

Another recommendation would be to look into rural cities and make changes there. The amount of activity overall in rural cities is significantly less compared to all other types of cities. This low activity creates larger average fares and fewer opportunities for drivers to find work. Pyber should look into creating incentives for riders and drivers in rural cities to help spur more business. These incentives could include bonuses for drivers or free ride promotions for riders. 

According to the data frame, the average fare for a driver in urban cities is $16.57 which is the lowest among all the other city types. Urban cities generate the highest fare total and therefore play a bigger role in Pyber's demographic values. The CEO should consider increasing the margins for urban drivers and help even the playing field for drivers across all city types. 
