# Pyber Analysis

## Overview
PyBer, a ride-sharing company, has asked us to find the following information about their rides, in urban cities, suburban cities, and rural cities.

1. The total number of rides
2. The total number of drivers
3. The total amount of fares
4. The average fare per ride
5. The average fare per driver

In addition, using the total fare by city type, create a graph of these fares over time for each city type.

## Resources
- Data Source: city_data.csv and ride_data.csv
- Software: Python 3.7, Jupyter notebooks, matplotlib

## PyBer-Analysis Results
The analysis of the election show the following table:
![data_table](https://github.com/bchillman/PyBer_Analysis/blob/main/Analysis/Data_Table.png)

As we can see, the total rides, total drivers, and total fares all increase as we go from rural areas to suburban areas to urban areas. Conversely, the average fare per ride and average fare per driver decrease as we go from rural to suburban to urban. This all makes sense, as the urban areas are more populated and thus have more people who need rides, and witht that demand there is a need for more drivers. However, since there is more demand the price per ride and the price per driver is *driven* down and we can see that these prices are lower in the more populated areas.

We can also look at the total fares by city type over time. This was done for 2019 from the months January to April, as seen below:
![graph](https://github.com/bchillman/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

As expected, the urban fares are always much higher than suburban, which are higher than rural fares. In addition, there does not seem to be 
## PyBer-Analysis Summary
### Business Recommendations
From thee results, we can make 3 business recommendations. First, PyBer can attempt to market more to suburban and rural areas. While it does make some sense that there are fewer rides in these areas, PyBer can attempt to close this gap with effective marketing strategies. Second, since the average fare per ride in the rural and suburban areas is significantly higher, PyBer can offer sign-up bonuses to new drivers in these areas. This will increase the number of drivers in these areas and lower the cost per ride. Finally, PyBer can potentially add incentives to drivers to drive on days that there may be spikes in needs for rides (weekends or holidays) to keep the fare per ride on those days slightly lower, as well as making sure there are enough drivers.
