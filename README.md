# bikesharing:  NY Citibike with Tableau
## Overview:
Explain the purpose of this analysis.
 there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

To prepare this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype and then exported the new csv in order to create the visualizations. 

## Results
Describe the results/key outcomes of each visualization underneath the image/pitch to investors.

### length of time that bikes are checked out for all riders and genders

This line graph displays the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.
![image](https://user-images.githubusercontent.com/102322707/179815100-8c6c3b37-4ee2-4a19-a852-a1d4185e0ce9.png)

This line graph displays the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.
![image](https://user-images.githubusercontent.com/102322707/179815193-66a9be8b-354e-48bf-99dd-2baa8b5d23c2.png)

### number of bike trips for all riders and genders for each hour of each day of the week

The following heatmap shows the number of bike trips for each hour of each day. It appears that the most popular time to rent is on the weekends, along with regular commuter times during the weekday (the hours of 5PM, 6PM, and 8AM, respectively.) There is a substantial amount of rentals throughout the day from 7AM up until 9PM, with rentals winding down between the hours of 9PM to 6AM.

![image](https://user-images.githubusercontent.com/102322707/179815385-99bea8e6-e3dd-4ddc-94dd-7da5b3f81e77.png)


This heatmap shows the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender. 
![image](https://user-images.githubusercontent.com/102322707/179815766-d7166232-081d-4b1f-bb0a-b33316ecc2ee.png)



### number of bike trips for each type of user and gender for each day of the week.
This heatmap shows the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

![image](https://user-images.githubusercontent.com/102322707/179815911-94758978-2318-404d-b705-9240538377ab.png)



### Locations
Created Dashboard of Top Starting and Top Ending Locations for comparison.
![image](https://user-images.githubusercontent.com/102322707/179816028-a02b62bb-51df-4045-8b3b-5d1d445ddfee.png)

### Subscribers
![image](https://user-images.githubusercontent.com/102322707/179827059-5a760ed5-4b82-461d-9767-6448923f2664.png)

Dedicated subscribers make up the bulk of rentals.  

## Summary
Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

### Popular Age Groups
![image](https://user-images.githubusercontent.com/102322707/179822273-7e79bbfa-1cc2-4130-a832-30b7b2b007cf.png)

### Bike Utilization


## Resources:
Data:  updated_201908-citibike-tripdata.csv

Software: jupyter notebook, Tableau

Other:
