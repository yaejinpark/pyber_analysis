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
### 


### Recommendations
Any specific landmarks around specific towns?
Ride duration - are rural areas avoided by drivers due to likely chance of long drives? Does it include tips? Start and end locations
Fare details - are tips included?