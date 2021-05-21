# PyBer_Analysis

### PyBer Module 5 Challenge

## Overview of the Analysis

PyBer CEO has asked us to create a DataFrame of the Ride SHaring data by city type, along with a multiple line graph displaying the weekly fares for each city type over a selected time-frame. 


## Results

Results of the analysis display sever large, but not unexpected, differences betweent the three city types. Urban cities bar far account for the largest number fo total rides, followed by Suburban and Rural cities, likely due to the larger population density from Urban to Rural cuty types, along with density of activities. The average fare per ride followed an inverse relationship to the total number of rides; this is likely due to the increase in distance between residences and activities found in Rural cities relative to Suburban and Urban cities, leading to longer rides. Lastly, the average fare per driver was highest in the Rural cities, followed by Suburban and Urban cities, likely due to the longer rides necessary in Rural cities. Additionally, there are more total drivers in Urban cities than total rides, further lowering the average fare earned per driver. The aforementioned resultes are shown in the table below:

![PyBer Summary DataFrame](https://github.com/curtissmith291/PyBer_Analysis/blob/main/analysis/pyber_summary_df.png)

Analysis of weekly fares earned per city type was plotted on a multiple line graph from 1 January 2019 to 29 April 2019, and is presented below. 

![PyBer Total Fare by City Type](https://github.com/curtissmith291/PyBer_Analysis/blob/main/analysis/Pyber_fare_summary.png)

As shown on the graph, Urban fares account for the majority of total fares earned, as expected. 

## Summary

Recomendations addressing disparities between the city types are presented below:

1) The total drivers is significantly higher than the total rides in Urban cities (2,405 and 1,625, respectively); consider removing the drivers who are inactive. 
2) Though additional analysis is necessary, the average fare per driver in Rural cities is relatively high. While longer drive times could explain the higher average, lower supply of drivers could increase rates; if the demand for drivers is higher than supply, consider increasing the percentage earned by the driver to incentivize more drivers to join PyBer. 
3) Extending the graph to include the the end of the data (the week of 12 May 2019), shows a drastic decline in total fares in every city type; additinoal analysis is necessary to determine the cause. The graph is included below. 

![Pyber Total Fare by City Type (Expanded Dates)](https://github.com/curtissmith291/PyBer_Analysis/blob/main/analysis/pyber_summary_df.png)
