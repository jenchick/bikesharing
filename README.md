# Bikesharing:  NY Citibike with Tableau
## Overview:
This analysis was created to help convince investors that a bike-sharing program in Des Moines is a solid business proposal. One of the key stakeholders requested a bike trip analysis, which has been prepared using Tableau.  The data utilized was for the month of August. 

To prepare this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype and then exported the new csv to create the visualizations in this proposal.

Please use the following [link](https://public.tableau.com/views/Citibike_Challenge_16581173552890/Story1?:language=en-US&:display_count=n&:origin=viz_share_link) to view the Tableau Story: 


## Results
The key outcomes of this analysis are outlined below.  

### Who is riding?
Everyone is riding!  The number of rides tapers down for the oldest and youngest of riders, but the following graph is evidence that riding is for everyone.

![image](https://user-images.githubusercontent.com/102322707/179822273-7e79bbfa-1cc2-4130-a832-30b7b2b007cf.png)

### Trip Duration

The following line graph displays the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.  It appears that bikes are checked out for all lengths of trip activity including quick (<10 minutes) up to longer trips (>45minutes.)

![image](https://user-images.githubusercontent.com/102322707/179815100-8c6c3b37-4ee2-4a19-a852-a1d4185e0ce9.png)

The next line graph displays the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.  It appears that quick trips (<10 minutes) are most popular for male and female riders, while the unknown gender indicated a popularity for longer trips (up to 25 minutes).

![image](https://user-images.githubusercontent.com/102322707/179815193-66a9be8b-354e-48bf-99dd-2baa8b5d23c2.png)

### Days and Times

The following heatmap shows the number of bike trips for each hour of each day. It appears that the most popular time to rent is on the weekends, along with regular commuter times during the weekday (the hours of 5PM, 6PM, and 8AM, respectively.) There is a substantial number of rentals throughout the day from 6AM up until 9PM, with rentals winding down between the hours of 9PM to 6AM.

![image](https://user-images.githubusercontent.com/102322707/179815385-99bea8e6-e3dd-4ddc-94dd-7da5b3f81e77.png)


The following heatmap shows the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.  It appears that the male and female categories mirror each other by day of week and time, with males showing greater utilization.  The unknown category does not appear to generate substantial results.

![image](https://user-images.githubusercontent.com/102322707/179815766-d7166232-081d-4b1f-bb0a-b33316ecc2ee.png)

### Subscribers vs Single Use Riders
This pie chart supports that dedicated subscribers make up the bulk of rentals.  The cost of a subscription is currently $185 (annual) or $15.42 (monthly). Single trips cost $3.99 while a day pass is $15 (https://citibikenyc.com/).  

![image](https://user-images.githubusercontent.com/102322707/179844046-52c99c1d-c913-4a0b-8e60-d9e5ffb39c7b.png)


This heatmap shows the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.  The bulk of the ridership is being done by male subscribers.

![image](https://user-images.githubusercontent.com/102322707/179815911-94758978-2318-404d-b705-9240538377ab.png)

### Locations
The following dashboard was created to show the most popular locations to start and end rides.  It appears that the starting and ending locations are symmetrical to each other with the bulk of the rides happening downtown. 

![image](https://user-images.githubusercontent.com/102322707/179816028-a02b62bb-51df-4045-8b3b-5d1d445ddfee.png)

## Summary
The NY Citibike program is incredibly popular and successful.  This program could easily translate to the city of Des Moines!  Considering the city’s 68 miles of paved trails (which serves as a nucleus to over 550 miles in Central Iowa), with users taking over one million trail trips annually throughout the year, (https://www.dsm.city/departments/parks_and_recreation-division/places/trails.php), this program would be useful to residents and tourists, alike!  Whether its biking for exercise, commuting, or adventure, the NY Citibike data shows that bikes are in demand. 

It also important to note that in its first six months of operation, NY Citibike gained over 100,000 subscribers.  Overall, the program has become integral to the daily commuters of New York City, along with being utilized by tourists, and is happening even during the snowy, wintery months! (https://wagner.nyu.edu/rudincenter/2014/02/why-citi-bike-so-successful)

In order to further explore this business opportunity, I would recommend the following additional analysis be performed, including:

1.) A visualization showing the population and tourism numbers for New York City compared to Des Moines in order to properly scale the program; and

2.) A visualization that explores the number of trips for each month of the year to explore seasonality of the program; and 

3.) A visualization that explores the number of rides by customer type (subscribers and single use riders) over the first five years of the program to explore program expansion and sustainability. 

## Resources:
Data:  updated_201908-citibike-tripdata.csv

Software: Tableau, jupyter notebook


