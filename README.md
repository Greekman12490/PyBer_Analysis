# PyBer_Analysis

## Overview of the analysis

###   V. Isualize has given Omar and I a new assignment to complete. We were tasked to create a summary dataframe of data consisting of ride-sharing in city types. These city types consist of urban (core of a city), suburban (outskirts of a city) and rural (areas outside the bounds of a city). Once the dataframe has been created, we will utilize the graphing interface of Python (matplotlib) via Jupyter Notebook to graph the totals of each city types weekly fares.


## Results

###   When we look at the dataframe, you will notice that the averages (regardless for fare or per driver) are higher in the rural areas than that of the suburban and urban areas. (DB Summary image (first picture)) One must take into account that rural areas consists of higher land usages compared to that of the suburban and urban areas. Higher land usages equals greater distances between locations. We can take this assumption and apply it to the suburban areas. The land usage won't be as high compared to that of rural areas, however, it is much greater than that of an urban area. (Area Coverage image (second picture)). If we look at the total rides and/or total drivers, you will notice that opposite of that we see with the averages. The urban areas will have more rides and/or drivers compared to that of suburban and rural. Now, why is that? We can make several assunptions. One, areas become more dense as we move closer to the core of the city (urban). More density of land uses also means high population density. The more populated, the more fares are needed. The more fares are needed, we will need more drivers to compensate. Two, with more drivers needed, fare prices should be lower due to more drivers are relatively available. For those in economics, this is a perfect example of the supply and demand curve. If we look at the curve (SND Example (third image)), Price is related to the fare price, and Quanity is related to the amount of drivers.

### ![DB Summary](https://github.com/Greekman12490/PyBer_Analysis/blob/main/analysis/Dataframe_analysis.png?raw=true)
### ![Area Coverage](https://github.com/Greekman12490/PyBer_Analysis/blob/main/Resources/city_type_areacoverage_example.png?raw=true)
### ![SND Example](https://github.com/Greekman12490/PyBer_Analysis/blob/main/Resources/forces-of-supply-and-demand_body_4.png.full.png?raw=true)

### When we look at the graph (below image), you will notice that overall, urban totals will be higher compared that to of suburban and rural areas. If we recall, more drivers, more rides, more fares all equates to what we see.

### ![Graph](https://github.com/Greekman12490/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png?raw=true)

## Summary

### Now, considering all that was analyzed, it is inevitable for the data to look that way due to demographics. However, we can distribue the amount of drivers throughout all city types. This would help out the rural and suburban areas, but, it will come at a cost of the urban area with drivers. With the distribution of drivers, we can adjust prices to compensate the inflow and outflow. However, unlike before, this will help out the suburban and urban areas. But, it will come at a cost to the rural areas in pricing. This will essentially cause a temporary equilibrium. However, with the nature of demographics, it may fall back to where it was originally.
