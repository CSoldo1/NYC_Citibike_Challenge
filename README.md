# NYC_Citibike_Challenge

## Overview
My objective is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. Using Tableau, I analyzed bike trip data from New York City and solidified my proposal with several visualizations. 

## Resources
* Tableau Public 2022.4
* Python
* Data: 201908-citibike-tripdata.csv from https://citibikenyc.com/system-data

## Analysis
Before I could upload the data into Tableau, the data type of the "tripduration" column needed to be changed from and integer to a datetime to get the time into hours and minutes. I completed this transformation using Pandas (refer to NYC_Citibike_Challenge.ipynb). 
![Transformed Data](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/transformed_data.PNG)

I then uploaded the "new_tripdata.csv" into Tableau. 

## Results
You can find the full analysis in the Tableau Story [here.](https://public.tableau.com/app/profile/christy.s.8692/viz/NYC_CitiBike_Challenge_16745773169170/Story1?publish=yes)

The majority of CitiBike trips last less than one hour.
![Trip Duration](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/Checkout_Time_For_Users.PNG)

CitiBikes are rented frequently during the morning and evening. More than likely, customers are using the bikes to commute to and from work. On the weekend, bike rental frequency is relatively equal throughout the daylight hours. 
![Trips By Weekday Per Hour](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/Trips_By_Weekday_Per_Hour.PNG)

The majority of CitiBike users are male. However, gender does not seem to play a role in trip duration. 
![Gender Breakdown](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/Bike_Use_By_Gender.PNG)

![Checkout Times By Gender](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/Checkout_Time_By_Gender.PNG)

As shown above, CitiBikes are frequently used to commute to work. Females are less likely to rent CitiBikes compared to their male counterparts - a trend most likely due to the common female business attire (i.e. dress, skirt, high heels, purse, hairstyle).
![Trips By Gender](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/Trips_By_Gender.PNG)

Even among the subscribers, bikes are most often rented during the work week. Again, males are the most frequent users and most frequent subscribers. 
![User Trips By Gender By Weekday](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/User_Trips_By_Gender_By_Weekday.PNG)

New York City is a dense, urban environment. The majority of rental bike users may live and work within a relatively small area, making bike usage very convenient. Furthermore, NYC attracts millions of tourists every year. Bike rentals are a great way to travel around the city quickly without having to pay for expensive rideshares or having to navigate the subway. 
![End Trip Location](https://github.com/CSoldo1/NYC_Citibike_Challenge/blob/main/Images/trip_end_location.PNG)

## Summary 
In NYC, weekday commuters use the CitiBike rental service most often, with males making up the vast majority of overall users. This may be an issue for service in Des Moines because the city is not as dense as NYC. If most citizens that work in the city live within the outlying suburbs, then the program may not be as popular. I would like to see a map of where most male residents live and work. If the commute time via bicycle is less than an hour (which seems to be the longest ride most patrons are willing to take) then CitiBikes seem like a viable option for the city. Furthermore, Des Moines lacks a subway system, so an affordable alternative to public transportation may be in high demand. However, Des Moines receives about 10 inches more snowfall per year than NYC, which may limit use and increase repair cost (i.e. rust). 
