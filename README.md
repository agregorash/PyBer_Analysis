# PyBer Ride-Share Analysis

## Project Overview

Shortly after starting as an analyst for a ride-sharing company, PyBer, I have been tasked with analyzing two sets of data, [city_data.csv](https://github.com/agregorash/PyBer_Analysis/blob/main/Resources/city_data.csv) and [ride_data.csv](https://github.com/agregorash/PyBer_Analysis/blob/main/Resources/ride_data.csv) in order to discover trends that exist amongst three categories of city types: Urban, Suburban, and Rural.  After merging the data sets through their common variable, city name, I was able to calculate total counts and averages of the three main variables: rides, drivers  and fares.  Finally, I visualized the results through various types of charts and graphs in Jupyter Notebooks, in order to present the findings to the CEO and offer analytics driven business proposals for improvement.

## Resources
- Data Sources: [city_data.csv](https://github.com/agregorash/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/agregorash/PyBer_Analysis/blob/main/Resources/ride_data.csv)
               
 - Software: Python 3.8.3, Jupyter Notebooks, Anaconda 3 

## Results
On a surface level, it is evident that Urban cities generally have the most drivers and rides, but the lowest fare.  Rural cities tend to have the least amount of drivers and rides, but the highest fare; while the Suburban cities lie in the middle for these three variables.

![Scatterplot-overview](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig1.png)
### Ride Data
![Ride-box-wisk](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig2.png)

A deeper look at the ride count data shows that Urban cities averaged about 24 rides, with a standard deviation of about 3.5 and one outlier in the dataset at 39 rides; Suburban cities averaged about 17 rides with a standard deviation of 2.5; and Rural cities averaged about 6 rides with a standard deviation of about 1.5.                                
![Ride-pie](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig6.png)

Urban cities accounted for about two thirds of the total ride count, with Suburban cities accounting for about a quarter and Rural cities accounting for just 5%.

### Driver Data
![Driver-box-wisk](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig4.png)

Driver counts for Urban cities have a very large spread, 70 drivers with the min being 3 and the max totaling 73.  The average driver count is about 37 with a large standard deviation just over 20.  Suburban and Rural cities have a much smaller spread, of 24 and 8 respectively; and averages of 16 and 4 respectively.                               
![Driver-pie](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig7.png)

Urban cities account for just over 80% of PyBer's drivers in this data set.  Suburban and Rural cities make up less than a fifth of the total drivers.

### Fare Data
![Fare-box-wisk](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig3.png)

The average fare per ride data is the most evenly spread amongst the three categories of variables.  Rural cities have the highest spread, $48, and the highest average, about $37.  Suburban cities have an average cost of about $31 and a spread of about $38; while Urban cities have the lowest costs, averageing just under $25 and a spread of $44.
![Fare-pie](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/Fig5.png)

Our total fare by cities does show that Urban cities still account for the majority of revenue generated with slightly less than two thirds of the total share; Suburban cities generating just over 30% of the total revenue share; and Rural cities generating just under 7% of total revenues.

## Summary
![Summary-line](https://github.com/agregorash/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

In summary,the data variables presented do show a very strong supply-demand relationship.  The driver count and ride count variables are directly related. In cities where more rides are being requested, there tend to be more drivers.  This relationship is most evident when comparing the Urban cities data to the Rural cities data.  At the same time the driver count and ride count variables are inversely related to the average fare.  When there are more drivers, fares tend to be lower and vice versa.

This analysis has revealed disparities between the three categories of city types with regard to the variables we analyzed.  Urban cities as a whole have the highest ride count, driver count, and the lowest average fare; but at the same time produce the most revenue.  Suburban cities are intermediary in all of the listed variables, and produce about half of the total revenue that Urban cities produce.  Rural cities have the least drivers and ride counts, with the highest fares; but still have the lowest overall revenue portion by a large margin.  Rather than addressing the disparities between the three categories and trying to overpower the conventional nature of the supply-demand market, I would advise that PyBer focus on closing the gap between each individual city within the categories, most specifically in the Urban cities sector.  I have listed out a few recommendations below:
1. Perform market analysis on the bottom half of Urban cities in regard to ride count.  Determine if there is an opportunity to increase user adoption  in the lowest performing cities, in order to maximize revenue in the highest performing category.
2. Evaluate the bottom 50-25% of Urban cities in regard to driver count.  Are these the same Urban cities that have the lowest ride counts? If so, focus on user adoption which should naturally increase driver count; if not, look into short term driver incentives to increase drivers and serve the customer base.
3. Look into driver incentives in Suburban cities, which account for abouT 26% of total rides and  30% of total revenue but just 16.5% of the drivers.  This could reduce user costs and result in even more revenue generated from Suburban cities 
