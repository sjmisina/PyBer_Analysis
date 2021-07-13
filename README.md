# PyBer Ride-Sharing Analysis  
  
## Project Overview  
  
Analyst:  Stan Misina  
Source Data: city_data.csv, ride_data.csv (client provided)  
Source Code: Python v. 3.8.8 with libs: pandas as pd, and matplotlib.pyplot as plt  
  
Project Date: 2021-07-13  
  
### Abstract  
We have been tasked with providing analysis of ride-sharing data across the first four months of Y2019 (Jan-Mar) for PyBer. We provide this overview focused on the three city 'types' as defined by PyBer: Urban, Suburban, and Rural.  
  
Found herein is an analysis for the three city types for the time period. We have also provided a multiple-line graph to demonstrate the total weekly fares over this time period by city type.  
  
  
## Results  
  
![PyBer Analyisis Summmary](/analysis/PyBer_Summary.png "Pyber Analysis Summary")  
  
Urban city fares make up the bulk of all individual rides for the region at about 72%, with Suburban providing 27% and Rural contributing just over 5% of overall business. Number of drivers totally servicing the analyized area is naturally skewed toward Urban cities, accounting for just under 81% of the total drivers, followed by Suburban and Rural at 16% and less than 1% respectively.

With greater business had in Urban areas, we see average fare per ride and per driver ranking lower than the Suburban and Rural areas greatly, with the highest average fair per driver coming in the Rural areas at $55.49, followed by Suburban at $39.50, and $16.57 for Urban drivers.  
  
![Total Fares by Week](/analysis/fare_by_type.png "Line Graph - total fares by week")  
  
Total Fares incoming for PyBer is consistently distributed across the city types over this timespan with some deviation in early April. There is further evidence of some volitility with Urban fares which we recommend reviewing this data against events in these areas that could effect these results.  


## Summary  
  
Based on this analysis, we offer the following takeaways:
  
  * Primary revenue generation certainly comes from servicing the Urban areas; however this has the highest concentration of drivers. Average fare per driver being less that the average fare per ride may suggest that the market is saturated with drivers.
  * Total fares are consistently presented across the timeline for the three classes, with the exception of April where there is fluxuation in the Urban sector. This could present opportunity to manage availablity according to the time of year regarding civic activity.  
  * Average fare per driver in Rural areas is much higher than the average fare per ride, indicating that there could be opportunity for expansion of drivers in rural markets.
 
