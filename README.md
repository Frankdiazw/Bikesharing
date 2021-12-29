# Bike sharing using Tableau

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Bike-sharing.jpg)

## Overview of the statistical analysis
New York City is known for being a very populated city (27,000 people per square mile), in consecuence, The Big Apple tops the list of most congested cities in the United States, with 102 lost hours in traffic in 2021. On a worldwide scale, New York City places fifth among the most congested cities. In order to avoid this traffic and also enjoy the view of the city, citizens of New York and outsiders tend to walk and ride a bike to get to their destinations, tour, etc.

All that being said, a privately run public bike sharing system serving part of New York City was established, "Citi Bike". Now, it is the largest bicycle sharing program in the United States. The system opened on May 27, 2013, with 330 stations and 6,000 bikes. This system has allowed this company to position itself as a top and important private company for the Big Apple. The idea of this module is to analyse the circumstances to propose a similar bike sharing system that can provide their services to a new city called Des Moines, capital of Iowa.

The layout of Des Moines is far more rural than New York city, each with a population per square mile of 2,515.6 and 27,012.5 respectively (ref 1). With a smaller population density Des Moines city will be able to easily implement bike lines for increased bike safety, along with bike paths through green space. These small infrastructure upgrades will increase the number of riders, as biking becomes less risk averse throughout the downtown city area, and even Greater Des Moines are, all this will be visualized using Tableau to visualize the data in a very neat way.

## Results
For this analysis of the bike sharing data, several points to visualize were proposed in order to create a high-level analysis. The results were the following:

### **Number of Trips**

For this result, a series of data were conglomerated that represent the total number of rides per category. First it can be seen that the total number of rides was 2,344,224.
From this amount of rides, analyzing the pie chart, it can be seen that most of the customers who used this service were male.

Then, the clients that lasted the longest using the service on average were born in the year 1970. Which means that by August 2020 they would be around 50 years old.
All this determines that to put a similar service in Des Moines, Iowa. It is expected that most of the clients will be this age and gender.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/NYC_citibike.png)

Figure 1. Dashboard for the NYC Citi Bike trips.

### **Peak Riding Hours in August**

For this result, a horizontal bar graph was made that shows the relationship of the 24 hours of the day with respect to the number of trips that took place during the day.
In the graph you can see that the time with the highest number of rides was at 5:00 p.m., followed by 6:00 p.m. This determines that for two hours a day a higher proportion of bicycle rental can be observed compared to the others.

It can also be seen that the time with the fewest number of rides was at 3 and 4 in the morning respectively. This is expected since most people use these hours to be able to rest.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Peak_riding_hours_august.png)

Figure 2. Graph of peak riding hours in the month of August.

### **Top Start Bike Stations and top End Bike Stations**

For this result, in Des Moines the latitudes and longitudes of the bike stations must be obtained to determine future safe routes for customers and provide them with strategic locations so that they can obtain a quality route.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Top_Locations.png)

Figure 3. Map of the top start and end Bike stations.

### **Checkout Times**

For this result, the graph of number of trips by duration show that the vast majority of trips taken on Citi Bike bikes are under an hour in length.

Like it was mentioned above, the majority of customers turned to be male, it can be seen also in the graph that the male gender outcomes the other genders.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Checkout_times.png)

Figure 4. Line Graph of the check out times for user and gender.

### **Trips by Weekday for Each Hour**

As mentioned above, the peak hours for the rides were at 5:00 p.m. and 6:00 p.m. respectively. In this heat map, we can also observe that the darkest squares are reflected at 5:00 p.m. and 6:00 p.m., more specifically on Thursdays and later on Tuesdays.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Trips_by_weekday_per_hour.png)

Figure 5. Heatmap of the trips in each weekday per hour.

The map is now divided by male and female, and almost the same results are reflected as the previous heat map, only this time the dark color is reflected a little less in the women's heat map, this is due to that they consumed less service.

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/Trips_by_weekday_per_hour_gender.png)

Figure 6. Heatmap of the trips by gender per hour during a weekday.

### **User Trips by Gender by Weekday**

In the same way, another heat map was created again, and this time they were divided by subscribers and customers. Almost the same results can be observed.
For Des Moines (215,636 habitants), somewhat similar results are expected, only that the heat maps should be a little clearer, since fewer people live in that city than in New York (8,419 million habitants).

![](https://github.com/Frankdiazw/Bikesharing/blob/main/Images/User_trips_by_gender_by_weekday.png)

Figure 7. Heatmap of number of bike trips broken down by gender for each day of the week by each Usertype.

## Summary
From this analysis we can understand that although New York and Des Moines are starkly different in size in population, there are some universal factors that can be implemented in both places. Understanding that the population of New York outcomes by far the population of Des Moines, means that the graphs and heatmaps will be different, but we can expect that the locations of the stations need to be in strategical and popular places where people can use the bike sharing service.

We can expect more male customers than other gender customers, and peak hours between 5:00 P.M. & 6 P.M. and minimum hours past 12 A.M. However this new service in Des Moines will be slower than in New York, we can expect good results if the company adjusts cuantity of bikes and stations to the city.
