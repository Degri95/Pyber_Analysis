# Pyber_Analysis
Analyzing rideshare data with python, Jupyter Notebook, pandas, and matplotlib

## Overview
 In this analysis we'll get driver and fare metrics for the ride-share company PyBer, and create visualizations of the data for the CEO of the company. After the data has been extracted and visualized, we'll compare the metrics of the three city types PyBer operates in. 

 - Urban
 - Suburban
 - Rural
 
## Results
First, we created a summary DataFrame of the ride-sharing data by city type. 
![PyBer Metrics DataFrame](/analysis/dataframe.PNG)

Examining the DataFrame, we can see that there are several key findings within.

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
![Total Fare by City Type Chart](/analysis/PyBer_fare_summary.png)