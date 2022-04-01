# PyBer_Analysis

## Overview of the PyBer_Analysis
### Purpose of the analysis

In the previous module we had already done some analysis on the city and ride dataset and created some graphs - Scatter chart for each city type with total number of rides and average fare; box-and-whisker plot for each city type to find the outlier on fares, number of rides, number of drivers; pie charts for each city type to compare with the total rides, total fares, and total drivers.

The purpose of the analysis is to use Pandas and Matplotlib to have a deeper analysis and to see how our data differs by city type and provide recommendations for addressing any disparities among the city types.

In this challenge we had created a summary DataFrame showing the average fare per ride and drivers, and some other information for each city types; we created a new DataFrame showing the sum of fares of each city type and date; we also created a pivot table to get total fares for each city type by date. At the end we created a multiple-line graph (fivethirtyeight) that shows total weekly fares for each city type.

## Results:

Based on Summary DataFrame:

![pyber_summary_dataframe](https://user-images.githubusercontent.com/100378319/161168668-a67ba109-caa0-4597-89d4-124a98da2063.png)

- For the Total Rides, there are 1,625 total rides in Urban, which is 1000 and 1500 more rides than Suburban and Rural which is normal because Urban has more population and density than Suburban and Rural so there are more customers.

- For Total Drivers, there are 2405 drivers in Urban, which is 1915 and 2327 more than Suburban and Rural drivers, the reason is because there are more demands (customers) in Urban city that will require more supply (drivers) based on the population of city;

- For Total Fares, there are $39,854.38 total fares for Urban city, which is $20,498.05 more $35,526.45 than Suburban and Rural, this is because there are much more total rides and customers from Urban that's why the total fares are much higher;

- For Average Fare per Ride, Urban is $24.53, Suburban is $30.97, and the highest is Rural $34.62. The main reason is because the distance of each ride in Rural is longer than urban and Suburban, the longer distance takes more time so the average fare per ride in Rural and Suburban is higher than Urban where the distance of ride is relatively short.

- For the Average Fare per Driver, the Urban driver is $16.57, Suburban is $39.50 and the highest is Rural driver which is $55.49. The reason is because their average distance of each ride is relatively longer than Suburban and Urban city, that's why the Rural drivers earn more fare than Suburban and Urban drivers averagely.

- For the 538 graph, it's showing the total fare by each city type from the date of Jan 6, 2019 to April 28, 2019 in weekly basis. 
The total fare of Urban is highest among the others which is the top line of the graph, the Suburban is in the middle line and the bottom line is Rural which is the lowest total fare. The main reason is because there are more population and more rides in Urban city than other city types. There are more demands so that's why Urban has the highest total fare.

![PyBer_fare_summary](https://user-images.githubusercontent.com/100378319/161168790-5b897b4e-552c-45f3-b70b-b61a331a437c.png)


## Summary: 

There are three business recommendations for the disparities among the city types.

1. The total drivers between the city type are so much different. There are only 125 drivers in Rural even average fare per driver is highest. One of the reasons is probably the total rides is much less among the cities so it is discouraging drivers to work in Rural. We can have another analysis on Rural such as competitors’ information, distance of each trip, geographic size, or discount offer in Rural to attract more customers in Rural in order to balance the total drivers for different city type. 

2. We can do a further analysis on the population and travel distance for each city type to understand more why the average fare per ride and driver in Rural are much higher, is it because of the travel distance, or is it because of the population size? So, we can adjust the fare of each city to balance out based on the analysis.

3. Total fares in Urban is much higher than other two city type, because there are more total rides and population in Urban. There are much more opportunities and potential revenue in Urban, company should invest more in Urban city such as deeper data analysis on different sectors, driver's customer service training, different time period promotion, etc. to generate more profit.

