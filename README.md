# PyBer_Analysis.

## Overview
PyBer, an upcomming comming competitor to Uber wants us to create a summary DataFrame of the ride-sharing data by city type. We will use the Pandas and Matplotlib, modules to create a multiple-line graph that shows the total weekly fares for each city type. Finally, in a written report we will summarize how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## Results

Let's take a look at table, that summarizes number of `Total Rides`, `Total Drivers`, `Total Fares`, `Avg Fare per Ride`, `Avg Fare per Driver` by each city type:

<img src="/analysis/pyber_dataTable.png" alt="pyberData_table_summary"><br>

As we can see Urban areas have the highest amount of drivers, and they are also the city with most amount of rides as well. They are also generating the most amount of revenue, despite having the lower fare costs. 

Although the other districts have lower ride count and total drivers compared to Urban, they do exceed in `average fare per ride` and `average fare per person`. This could be due to the fact that there is less supply of driveres, which will inevitably mean there will have fewer rides. By raising the average price per ride and driver, they are also increasing their revenue.  

Just from this table alone we can see that the:

- total rides
- revenue
- cost of fare per driver 
- cost of fare per ride 

are heavily affected by the number of drivers.

---

Let's take a look at the same data, in a different way and broken down even further. 

<p>
  <h3 align="center">Percentage of Total Fares by City Type</h3>
  <br>
</p>

<img src="/analysis/total_fares_by_cityType.png" alt="fares_by_city_type.png" align="left" width="350">

As we can clearly see, Urban cities are dominating when it comes to **percentage of total fares by city type**. In rank, Urban city comes in **first place**, with Suburban comming in at **second** and in last place with the least amount of fares, we have Rural cities. 
<br clear = "left"/>

---

<p>
  <h3 align="center">Percentage of Total Drivers by City Type</h3>
  <br>
</p>

<img src="/analysis/total_drivers_by_cityType.png" alt="total_drivers_by_city_type" align="left" width="350">

As we can clearly see, Urban cities are dominating yet again when it comes to **percentage of total drivers by city type**. In rank, Urban city comes in **first place**, with Suburban comming in at **second** and barely making it in last place with the least amount of drivers, we have Rural cities. This gives us a better understanding at the importance of having a larger driver count, and how it overall benefits the cities.  
<br clear = "left"/>

---


<p>
  <h3 align="center">Percentage of Total Rides by City Type</h3>
  <br>
</p>

<img src="/analysis/total_rides_by_cityType.png" alt="total_rides_by_city_type" align="left" width="350">

As we can clearly see, Urban cities are dominating yet again when it comes to **percentage of total rides by city type**. In rank, Urban city comes in **first place**, with Suburban comming in at **second** and with the least amount it in last place with the least amount of rides. This is again of course linked to the **decreasing number of drivers available**, and also the **increased amount of fare charges**.
<br clear = "left"/>

## Summary 

<p>
  <h3 align="center">Big Picture</h3>
  <br>
</p>
Finally, lets take a look at the big picture:<br>
<img src="/analysis/PyBer_fare_summary.png" alt="PyBer_fare_summary">

In this visual representation we come to the same conclusion. Urban is excelling in most areas, due to the increase in number of drivers, which has an impact on the number of rides, which also impacts the overall revenue the company generates from the cities. This again, has an impact on the cost per fare as well. Since the supply of drivers is less in other city types, we have higher fares to counteract that fact. Since the fare prices are higher, residents are less likely to use the service. 

Here are a few recommendations:

### Recommendation 1 - Best
Increase the number of drivers in cities with low count. We can create incentives to entice residents to signup as an Pyber driver. Doing this, should make drivers more available, which means more people can use the service and the rate for trips can also be lowered. Once we have matched the demand and supply has reached their equalibrium, we can start increasing our revenue.

### Recommendation 2 - Great
If increasing driver count is not an option, we should look into creating some sort of loyalty program for the residents. We can offer a free ride for every 10 they take. They can collect points for every trip, and use those points to purchase rides in the future. We can also make these points transferable to our friends and family. People love being a part of a comunity. So if this is advertisied correctly, it can be a great success.

### Recommendation 3 - Good
Another option we should consider is decreasing the fare rate, to attract more business. Once we have built that strong reputation with out customers and are getting repeat customers consistently, we can slowly start to increase the price back up.
