# PyBer-Analysis - Berkeley DA
Yae Jin Park\
Module 5 - PyBer with Matplotlib

## Overview
The main objective of this project is to become more familiar with data analysis with Pandas and Matplotlib. Two sets of data were provided, city_data.csv and ride_data.csv, each containing different sets of data but "connected" by city name columns. After merging these data sets, an analysis was done on the fares, number of drivers and city types. 

## Result
### Ride-Sharing Summary by City Type
The following dataframe that shows the summary of rides by each city types:

![Summary](https://github.com/yaejinpark/pyber_analysis/blob/main/analysis/Pyber_summary.png)

Urban cities have the highest number of drivers, rides and total fares. Rural cities have the lowest for the same categories. Interestingly, rural cities have the highest average fare per ride and average fare per driver. Suburban cities' fare data fall in the middle of the two.

Just from a glance, it's difficult to tell what these numbers indicate, so the ride data were plotted as shown below:

![Plot](https://github.com/yaejinpark/pyber_analysis/blob/main/analysis/PyBer_fare_summary.png)

As expected, fares from urban cities are at all-time high among the three city types, rural cities at the lowest, and suburban cities right inbetween. There are some dips and peaks for suburban and urban fares, urban more so during March, but rural fares plot doesn't have a specific dip although it does have occasional peaks.

## Summary
Previously, an analysis was done on how many drivers (in terms of percentage) completed the rides in each type of cities. An analysis was also done on % of fares for each city types. 

![Drivers in each cities](https://github.com/yaejinpark/pyber_analysis/blob/main/analysis/Fig7.png)

The pie chart above shows how drivers are distributed among the three city types. 86.7% of the drivers finished the rides in urban cities, where as only 0.8% and 12.5% did in rural and suburban cities, respecitvely. Though more analysis will have to be done on the suburban city ride data, it is clear that rural cities have a higher demand than supply of PyBer rides. Recall that there was no clear 'drop' in the fare summary plot for rural cities in the 'Ride-Sharing Summary by City Type' section. Even though rural cities had very few drivers complete rides, the fares of rides in the same cities took up 6.8% of total fares (three city types combined) as shown in the pie chart below:

![Fares in each cities](https://github.com/yaejinpark/pyber_analysis/blob/main/analysis/Fig5.png)

This could mean that drivers in urban cities can benefit more if some of them started rides in rural cities. 

### Recommendations
Here are three recommendations for the PyBer CEO: 

* Gather data on the ride duration: It is possible that rides in urban cities have a shorter duration than rides in rural cities. If this is the case, given that the difference in average fares between two city types is only about $10, drivers prefer to remain in urban cities for shorter ride duration for similar amount of fare. If this is the case, rural cities can suffer from shortage of PyBer drivers.

* Find out demand of PyBer rides in rural cities: As mentioned previously, rural cities may not have sufficient PyBer drivers. A survey can be done in some of the rural cities to see if there is indeed a shortage of PyBer rides that need to be met. If people in rural cities are satisfied with the number of drivers available, there is no need to 'fix' the current distribution of drivers among the three city types.

* Gather weather data: This applies more to urban and suburban cities. These two city types had visible peaks and drops in the fare summary plots, indicating there are some unknown factors that affect demands for PyBer rides. Said peaks and drops happened during spring (late February to early April), and one possible reason I can think of is the weather since spring weathers are unpredictable. Rainy days can increase demands of rides, whereas sunny days can drop the demands.