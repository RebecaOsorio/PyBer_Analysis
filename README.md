# Module 2 Challenge

## Overview of Project

### Background
This week, we worked in Data Visualizations along with Omar so we could analyze data of PyBer, a ride-sharing app company; from January to early May of 2019 and create a compelling visualization for V. Isualize, the CEO. 
In this final delivery, we have:
1. Created a summary DataFrame of the ride-sharing data by city type
2.  Created a multiple-line graph that shows the total weekly fares for each city type

##  Resources

* **Data Source:** `city_data.csv` and `ride_data.csv`

* **Software:** Jupyter Notebooks, Python 3.7.7, Matplotlib 2.2.2.


## Results

### Total Fare (resampled by week) by City Type. 
![PyBer_fare_summary](https://user-images.githubusercontent.com/90414330/139527820-3d05b0ef-e27d-4184-b998-58db1309cfb9.png)

It's clear that most of the Fares are coming from the Urban Cities and that the Rural ones almost get some Fares. But when we were working in the Statistics and Box-and-Whiskers plots, we saw that the Rural Cities are giving more Fares for each trip; so, what happens when we analyze the average fares per ride and driver, in the Summary DataFrame?

### Summary DataFrame
![Summary DataFrame](https://user-images.githubusercontent.com/90414330/139527878-35632c18-959f-41fd-bf1e-30d38eb5cee1.png)

In the Summary DataFrame we can see that the Rural Cities are having the smallest amount of rides, but in average, they are receiving more Fare per Ride and the Drivers are getting almost three times of Fare than a Urban Driver gets.


## Summary
Based on the results, we'll provide three business recommendations to the CEO for addressing any disparities among the city types.
1. We should increment gradually the drivers in the Rural Cities. If the people is paying more for the trips, that means that there is a high demand and we should increase the product. Although the fare per driver and maybe ride will decrease; hopefully,  we can increase the total amount of fares for the Rural Cities.
2. In contrast, I don't think that we should decrease the number of riders in the Urban City. Going into Detail, the niche of this app is the Urban Cities, there, the total amount of Fares was over the $2,000USD per week. But we should get into consideration that in the Urban Cities, the drivers aren't getting a decent amount of Fares, so we could quote some group benefits --insurance, lendings, etc.-- for them.
3. We can also increase the drivers for the Suburban Cities, but it should be when the Rural Cities get more Fares per Week.


> Written with [StackEdit](https://stackedit.io/).
