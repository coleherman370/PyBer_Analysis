# PyBer_Analysis

## Project Overview
Pyber has requested an exploratory analysis of their ride share data complete with data visualizations.

## Resources
Data Source: city_data.csv; ride_data.csv
Software: Python 3.9.6, Visual Studio Code 1.61.1

## Summary
Data was provided via two csv files. One [file](https://github.com/coleherman370/PyBer_Analysis/blob/main/Resources/city_data.csv) contained city information such as City name, number of drivers and City type. The second [file](https://github.com/coleherman370/PyBer_Analysis/blob/main/Resources/ride_data.csv) contained ride information such as City name, date of ride, total fare of ride, and a ride ID. These tables were combined on City name into a single file for the purpose of the analysis.

## Results

* [Plotting](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig1.png) Average Fare to Number of rides displays a strong negative correlation between the Average Fare and Number of rides. 
  * As the number of rides increases the average fare descreases.
  * This correlation may be attributed to city type as Urban ride shares on average may consist of more frequent shorter trips. Whereas, Rural ride shares have fewer ride shares overall but are likely to consist of longer rides.
  * While the average fare is [highest in Rural cities](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig4.png), Urban cities still perform the [highest volume of rides](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig6.png) and the [highest revenue from fares.](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig5.png)
* [Ride count data](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig2.png) supports the second explanation for the negative correlation.
  * Overall Rural cities have a significantly lower average number of ride compared to both Suburban and Urban cities.
* [Driver counts by city](https://github.com/coleherman370/PyBer_Analysis/blob/main/Analysis/Fig4.png) displays that Rural cities have a far tighter average of driver than Urban cities. 
  * This would also attribute to the correlation between fare and number of rides as the low availability of drivers would inherently drive up the fares as patrons have fewer options for available rides.
* A periodic analysis of fares of time show that trendline is fairly constant in Rural areas. Meanwhile, There appears to be a general upward trend of fares collected in both Urban and Suburban cities. ![](/Analysis/Pyber_fare_summary.png)

## Suggestions
In order to make this analysis more valuable, data for ride distance and ride type (if fare pricing is tied to vehicle type) would need to be made available. With the current data we are able to see the trend, but do not have the necessary data to draw reliable conclusions on the cause for the trends.