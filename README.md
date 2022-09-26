# NYC CitiBike Bikesharing Data Visualization & Analysis

## Overview

The New York City CitiBike bikesharing program is a well known and popular service in one of the world's largest and most highly trafficked cities. We have sourced data on the CitiBike program to craft an analysis centered around key data visualizations using Tableau. The aim of our analysis is to gather insights from data on the CitiBike bikesharing program to determine the viability of a similar program in Des Moines, Iowa and relay the supporting findings to potential investors looking to seed-fund the venture.

The data used for our visualizations is sourced directly from the NYC CitiBike website in its "system data" resource (https://ride.citibikenyc.com/system-data). We focused our analysis on CitiBike bikesharing data from August of 2019, as we wanted to look at recent data from an active, warm-weather month. The data source files were too large to include in this online repository, however, it may be downloaded from the link below.

Data Source (Zip Compressed CSV File): <br>
https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip

To view the data in our interactive Tableau Story, please visit the link below.

Tableau Public (Interactive Data Visualizations):
https://public.tableau.com/app/profile/kevin.eapen/viz/NYC_CitiBike_Challenge_Visualizations/NYCCitiBike

The following section contains 7 key data visualizations in our analysis, with a brief description of the results for each.

## Results

### Checkout Times for Users
![viz1](Images/Checkout_Times_for_Users.png)

This visualization plots the length of time that bikes are checked out for all riders. The curve of the charted line reaches at around 5 minutes, with 146,752 number of bikes being ridden for trips at this duration. The vast majority of trips last less than 30 minutes, and virtually no trips last more than 1 hour.

### Checkout Times by Gender
![viz2](Images/Checkout_Times_by_Gender.png)

The above visualization charts the length of time that bikes are checked out for all genders, with each gender represented by a different color line. The shapes of the curves suggest that the pattern of usage is similar across all genders, with male and females checking out a peak number of bikes for 5 and 6 minutes at a time (respectively) and other genders checking out peak number of bikes for a duration of 11 minutes. The sample size of the "unknown" category of genders is significantly lower, however, so the distribution of this data segment may not be as normalized. The data from this visualization also reveals that the male gender checks out many more bikes than any other gender, with a peak of 108,087 bikes checked out at 5 minutes trip duration. By comparison, the female gender peaks at 34,151 bikes checked out out at 6 minutes trip duration, and the "unkown" genders peak at 7,389 bikes checked out at 11 minutes trip duration. This means that users of the CitiBike program are predominantly of the male gender.

### Trips by Weekday per Hour
![viz3](Images/Trips_by_Weekday_per_Hour.png)

The above heatmap visualizes the number of bike trips by weekday for each hour of the day. The frequency of bike trips tends to heat up around the hours of 8AM, 5PM, and 6PM for days of the week Monday through Friday. On the weekend days (Saturday and Sunday), the frequency of bike trips is a more even distrbution throughout the day, with somewhat hotter activity hours between 11AM-6PM.

### Trips by Gender (Weekday per Hour)
![viz4](Images/Trips_by_Gender_(Weekday_per_Hour).png)

This heatmap displays the number of bike trips by gender for each hour of each day fo the week. The pattern of frequency of bike trips seem to be similar hours for each day of the week between male and female genders. Unknown genders do not display as clear a pattern throughout the week, however, this may be due to the relatively low number of users belonging to this category relative to the other genders. This may result in less differentiation between the lighter low frequency shades of the heatmap, making it harder to discern the pattern of use through heat maps for the unknown genders category. As in previous visualizations, this heatmap suggests males use the bikeshare program more overall, as the heatmap shows darker colors for the male gender chart, signifying a higher number of trips taken.

### User Trips by Gender by Weekday
![viz5](Images/User_Trips_by_Gender_by_Weekday.png)

The above heatmap shows the number of bike trips broken down by gender for each day of the week by each "Usertype". This visualization indicates that users of the male and female genders that are subscribers utilize the program more by taking more trips than non-subscribing customer usertypes of the two genders. The unknown genders category counters this tendency with the inverse being true for usertypes in this category. Users of the unknown genders category who are subscribers utililze the program less than non-subscribing customer usertypes by taking less trips. Additionally, Thursday is the most popular day for subscribing users across all gender categories, with the most number of trips taken on that day for each gender. Among non-subscribing customer usertype, the most popular day for renting CitiBikes is Saturday, and this is true across all genders of this usertype. 

### Bike Repairs (Number of Trips)
![viz6](Images/Bike_Repairs_(Number_of_Trips).png)



### Bike Utilization (Total Trips Duration)
![viz7](Images/Bike_Utilization_(Total_Trips_Duration).png)

## Summary