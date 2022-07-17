# Pyber_Analysis
Analyzing rideshare data with python, Jupyter Notebook, pandas, and matplotlib

## Overview
 In this analysis we'll get driver and fare metrics for the ride-share company PyBer, and create visualizations of the data for the CEO of the company. After the data has been extracted and visualized, we'll compare the metrics of the three city types PyBer operates in. 

 - Urban
 - Suburban
 - Rural
 
## Results 
![PyBer Metrics DataFrame](/analysis/dataframe.PNG)

We created a summary DataFrame of the ride-sharing data by city type. Examining the DataFrame, we can see that there are several key findings within.

### Total Rides
1. Urban had the most total rides at 1,625. 
2. Suburan had the second most total rides at 625.
3. Rural had the lowest total rides at 125.

### Total Drivers

1. Urban had the most total drivers at 2,405.
2. Suburban had the second most total drivers at 490.
3. Rural had the lowest total drivers at 78.

### Total Fares

1. Urban had the most total fares at $39,854.38.
2. Suburban had the second most total fares at $19,356.33.
3. Rural had the lowest total fares at $4,327.93.

### Average Fare Ride per Ride

1. Rural had the highest average fare per ride at $34.62.
2. Suburban had the second highest average fare per ride at $30.97.
3. Urban had the lowest average fare per ride at 24.53.

### Average Fare per Driver

1. Rural had the highest average fare per driver at $55.49.
2. Suburban had the highest fare per driver at $39.50.
3. Urban had the lowest fare per driver at $16.57.

While urban cities have the highest amount of total drivers and total rides, they have the lowest average fares. They are also the only city type with their total driver count higher than their total rides. Looking at the ratio of total drivers to total rides, the fare increases when the amount of drivers is lower than the amount of rides.

### Total Fare by City Type
This chart illustrates the total fare of each city type on a weekly basis from the beginning of January 2019 to the end of April 2019
![Total Fare by City Type Chart](/analysis/PyBer_fare_summary.png)

Urban city types had the highest total fare throughout the whole year, followed by suburban and then rural. After looking at the dataframes total fares this chart isn't something unexpected. The only noticeable peak between all three city types seems to be at the end of February. There also isn't any overlap between the city types total fares.

## Summary
- Urban cities generate most of the profit, but rural cities have a higher average fare. There may be other factors contributing to this such as longer driving distance. If the demand for rides was researched in rural cities, perhaps more profit could be made. ex: more drivers.

- The driver count in urban cities is the only city type with more total drivers than total rides. When looking at the other city types we see some correlation between higher fares with a lower driver count to ride count. If we could market to more urban city riders to increase the ride count the average fare should increase. 

- Looking into how many miles are traveled each ride is something that should be researched. The average fare may not have to do with the relationship between drivers and rides, but actual travel distance. It's definitely a limitation in this analysis that should be looked into in further research.