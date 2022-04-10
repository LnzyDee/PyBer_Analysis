# PyBer Analysis

## Overview

Creating and using a summary DataFrame of ride-sharing data by city type, then from that data, using Pandas and Matplotlib, creating a multiple-line graph that shows the total weekly fares for each city type and summarizing how the data differs by city type and how those differences can be used by decision-makers at PyBer.

## PyBer Analysis Results

### Results
- Urban ride-sharing, at a total of 1,625 total rides (as displayed below), surpasses those in the rural (125 total rides) and suburban (625 total rides) areas. Suburban comes out ahead of rural. 
  - These results show what would be expected in these city types. Urban areas are more populated and denser, allowing for more users. Suburban areas are less populated than urban areas, but often located just outside of urban areas, cities, allowing for a decent number of users. Rural areas are well outside of cities and very spread out, less populated, so unsurprisingly the amount of ride-sharing usage there is significantly less than their counterparts. 
- The number of drivers in rural areas is nearly half the number of total rides; going on from rural to suburban, we see a closer ratio of rides to drivers; when we get to drivers in urban areas, there's more drivers (2,405 drivers) than total rides (1,625). 
- Rides in rural areas are shown to spend more, averaging at $34.62 (as shown below), to get rides compared to urban, whose average came out to $24.53 (see below).
  - This price difference could be due to less usage in the rural areas and trying to make up that gap, also distance traveled could add to the rural average ride fare.

![PyBer Summary DataFrame](/analysis/PyBer_summary_df.png)

![PyBer Fare Summary](/analysis/PyBer_fare_summary.png)

## PyBer Analysis Summary

### Summary
- Considering Rural areas are more spread out, it might be useful for them to have more ride-sharing availability to allow for travel to wherever they need. 
  - Maybe finding more drivers to provide service to the rural areas could improve usage. 
- A big opportunity could be seized by getting more drivers as well in the Suburban areas, considering the bigger population compared to rural areas, it would be even more likely to find drivers to provide more of the ride-sharing service. 
  - Getting some of the urban drivers nearer to suburban areas to help increase service to that area would help improve the suburban user's ability to use the ride-sharing service.
- Increasing access in the lesser used areas could also help to lower costs for users, creating a better experience for them as well.

## Resources
- Data Source: [City Data CSV](Resources/city_data.csv),
[Ride Data CSV](Resources/ride_data.csv)
- Software: [Python](https://www.python.org/), 3.7.6, [Visual Studio Code](https://code.visualstudio.com/), 1.65.2, [Anaconda](https://www.anaconda.com/), [Jupyter Notebook](https://jupyter.org/)
