# Pyber_Analysis

## Project Overview
PyBer, a Python based ridesharing app company, is completing an exploratory analysis on data to understand the relationship between the type of city, and the number of drivers and riders, as well as the percentage of total fares between each category. The analysis is intended to help PyBer improve access to ride-sharing services and determine affordibility for underserved neighborhoods.

## Resources
- Data Source: city_data.csv, ride_data.csv
- Software:Python 3.7.6, jupyter-notebook 6.0.3, Anaconda 4.13.0, Pandas 1.0.1, Matplotlib 3.1.3

## Challenge Overview
V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Challenge Summary
The data was compliled and summarized in a dataframe for a comparison between the different city types, (Rural, Suburban, Urban). 

<p align="center">
A ride-sharing summary DataFrame by city type
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Pyber_Analysis/blob/main/analysis/Type_Ride_Fares_Summary.png" width="85%"/>
</p>


The differences amongst the 3 city types:

**Urban:** Has the most drivers employed and has provided the most rides. Due to the number of drivers staffed to the number of rides provided the the Average Fare per Driver is the lowest compared among the 3 types. Average Fare per Ride was also the lowest assuming the ride duration not being as far in distance when compared to rural cities. 

**Suburban:** Between all the data, Suburban cities finished 2nd in every comparison between Rural and Urban. The Drivers were better utilized with a 1.28 ratio of rides to drivers. Due to this reason, the Average Fares per Ride and Driver were both higher than that of the Urban cities.

**Rural:** Total Rides and Drivers were the lowest but showed that the Drivers were best utilized with a 1.60 rides to driver ratio. With fewer drivers, the margins were higher shown by the Average Fare per Driver being greater than 3.3 times that of the Urban cities. 


<p align="center">
A multiple-line chart of total fares for each city type
</p>

<p align="center">
  <img src="https://github.com/mcgibbenyd1/Pyber_Analysis/blob/main/analysis/PyBer_fare_summary.png" width="95%"/>
</p>

- Between the dates of 1/1/2019 and 4/28/2019 it can be seen that Urban cities had the most fares during the timeline and stayed steady throughout while followed by Suburban then Rural cities. 
 
## Overall Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
1) In order to increase margins for the Urban cities, the number of drivers needs to be decreased as there are not enough people riding compared to the drivers staffed.
2) To make the business more available the number of drivers can be increased in the Suburban cities.
3) The fares can be increased in the Urban cities to compensate for the number of drivers while maintaining an available presence for the consumers. 

