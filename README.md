# HW5-Matplotlib
## Pyber 

The ride sharing bonanza continues! Seeing the success of notable players like Uber and Lyft, I've decided to join a fledgling ride sharing company of my own. In our latest capacity, I'll be acting as Chief Data Strategist for the company. In this role, I'll be expected to offer data-backed guidance on new opportunities for market differentiation.

I've since been given access to the company's complete recordset of rides. This contains information about every active driver and historic ride, including details like city, driver count, individual fares, and city type.

I created a Bubble Plot that showcases the relationship between four key variables:

-Average Fare ($) Per City

-Total Number of Rides Per City

-Total Number of Drivers Per City

-City Type (Urban, Suburban, Rural)


In addition, I produced the following three pie charts:

-% of Total Fares by City Type

-% of Total Rides by City Type

-% of Total Drivers by City Type


As final considerations:

-I used the Pandas Library and the Jupyter Notebook.

-I usede the Matplotlib library.

-I included a written description of three observable trends based on the data as conclusions (below).

-I used proper labeling of your plots, including aspects like: Plot Titles, Axes Labels, Legend Labels, Wedge Percentages, and Wedge Labels.


## Conclusions

After completing the Pyber data analysis I could determine the following trends below:

- Cheaper by the dozen!: from the Pyber Ride Sharing Data bubble plot, it can be observed that when the number of rides increase, the average fare decreases, with a "cheaper by the dozen" effect, meaning that there's an apparent discount as a function of the number of rides
- Population density: On the same plot mentioned above, there's an implicit effect of number of drivers and fares depending on the population density. Urban areas have considerably more drivers and rides with respect to the rural ones. Because rural rides are less than their urban counterparts, fares tend to be higher, as most likely distance coverage should be higher as well (this would be another dataset to be requested for further analysis as cost per mile and cost per ride time).
- Allocation of drivers could improve! : Analysing the total fares and total rides by city type, it can be observed there's a ratio of 65% Urban, 30% Suburban and 5% Rural for both total amount of fares and number of rides, which seems healthy. However the number of drivers is considerably higher in the Urban areas, a quality survey could be recommended per city type to confirm the current number of drivers is enough or if we will need to recruit more drivers for Suburban and Rural areas.


