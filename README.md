

![]("../Resoruces/Citi_Bike_logo.jpg")

# CitiBike Analysis



The written analysis has the following:

- Overview of the analysis: Explain the purpose of this analysis.
Overview of the statistical analysis:

- Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image.
The purpose of the analysis is well defined. (5 pt)
Results:

There are at least seven visualizations for the NYC Citibike analysis (7 pt)
There is a description of the results for each visualization (7 pt)


 - Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset
Summary:

There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)


## Overview

We are proposing bringing the popular bike sharing company "Citi Bike" to Des Moines.  Before we do we need to examine available data to discover more about the way this program is utilized.  We will be working with the data gathered in New York in August 2019.  From this data we will be hoping to get a greater understanding of bike sharing and who uses the service by looking at popular rental hours, duration of rentals, etc  

## Resources
Tableau, Pandas library, Jupyter notebook

## Results

[Tableau CitiBike Story](https://public.tableau.com/profile/russell.shelley#!/vizhome/CitiBikeProject_16148927450710/WhoUsesCitiBike)


-  We start with a map of start and end locations. 
    - These are very similar. Customers are riding back and forth between nearby locations.

-![Start/Locations](../Resources/start_end.png)


- Looking at trip duration we see the majority of trips are very short around 5-10 minutes.

-![Trip Duration](../Resources/trip_duration.png)

- We can see that this pattern of short trips is repeated across genders. But there are many more male users.

-![Trip Duration By Gender](../Resources/trip_duration_by_gender.png)

- The pie chart displays this well. There are three times as many male users.

-![]()

- This heatmap of Stoptimes shows clearly that the busiest times are just prior to work/just after work, on weekdays. The CitiBike has become a part of the journey to the office. Weekend show usage throughout the day.

-![]()

- The next heatmap shows how the story is repeated across genders. (We may also notice that Wednesday is the quietest weekday--work from home Wednesday!)

-![]()

- This next pie chart shows that most trips are made by subscribers, not casual users.

-![]()

- Here it is illustrated that it is weekday, male, subscribers who take the most trips.  These are commuters, that have intergrated CitiBike as part of there daily routine.

-![]()








## Summary

 - From this data we can clearly see that most trips are made by loyal subscribers (~80%).  These subscribers are around 3 times as likely to be male over female. They are making short trips (around 5 mins), between work and public transit.
 This key demographic has made citibike part of there daily life.  They enjoyed the program enough to subscribe and they are using these subscriptions.  CitiBike stations, near Des Moines DART stops could become a positive part of many workers day!  

- Although most of the trips are of the short commute link type. I would like to see how the revenue compares with weekend trips and casual users.  
- From the user type and trip duration we could see the cost of each non subsriber trip.
- I would like to compare the revenue gained by non-subscribers/ to the revenue gained from subscribers. Are the casual riders more relevent than at first appears?  
- How do single ride($3) sales, look compared to day pass rides($15)? 