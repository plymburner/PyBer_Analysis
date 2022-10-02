## PyBer_Analysis
Module 5

## Overview of the Analysis

    The purpose of this project is to perform exploratory analysis of Pyber ride sharing data in order to gain an understanding of ridership and fare metrics by the types of cities in which Pyber operates, creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services, and determine affordability for underserved neighborhoods.
 
## Results

    The summary of PyBers ride sharing data, I have created a statistical overview and summary.

    https://github.com/plymburner/PyBer_Analysis/blob/main/Analysis/pyber_summary.png

    The results demonstrate numerous trends beyond the data.
        1. Population Density
            a. In more densely populated areas, there are obviously more people, yet there are fewer car owners due to the lack of parking or the expense of parking.
            
            b. There are more alternative transportation modes (buses, trains, subways) that puts pressure on fare rates for the lower end markets, less dense population centers tend to have fewer alternatives modes of transportation and car ownership is less expensive.
           
            c. With the increased cost of ownership of a car being inverse to the population density, drivers are more likely to take on part-time gigs (jobs) to help offset their costs. This higher number of drivers distorts the fare per driver metric because of the larger driver pools in urban cities.
           
            d. The increased population density increases the possibility of having one or more people living in the same neighborhood and working or regularly going to a destination in the city i.e. Brooklyn to the Financial District. This becomes less likely in other categories of cities because of few numbers and the more diffuse distribution of origins and destinations.
       
        2. Missing Critical Data
            a. Mileage
                i.  Mileage would provide additional descriptive and categorical (using bins) to demonstrate the relationship between fares and distance
            
            b. Revenue per Mile Metric
                i.  By being able to compare the revenue generation by city type, there is a common base to better understand the relationship between fare revenue and distance. This would remove the skew from the number of drivers and provide a better baseline for comparions across the city types. Regardless, each city type will have different distributions due to the geographic characteristics of the types of the cities and the transportation habits of the people who live in the cities.
                ii.  When looking at the fares per driver metric, it shows the urban drivers generate less revenue per driver than other city categories. This also leads to the inference that with many of these drivers have the opportunity to drive more often than their current part-time status.
        
        3. Under Utilized Capacity
            a.  Geographic Distribution
                i.  Digging deeper into the combinations of origins and destinations and looking into which areas are most traveled and look for ways to recruit or promote going to parts of the city that tend to have fewer or no riders as places to develop capacity and customers to increase future businsess.
                ii. Urban areas have the greatest potential with the greater market penetration and larger distribution for the number of rides
                    1.  https://github.com/plymburner/PyBer_Analysis/blob/main/Analysis/Fig2.png
                iii.Fares by City Type
                    1.  https://github.com/plymburner/PyBer_Analysis/blob/main/Analysis/Fig5.png
                iv. Total Available Drivers
                    1.  https://github.com/plymburner/PyBer_Analysis/blob/main/Analysis/Fig7.png           

## Summary

    Based on the analysis my business recommendations to Pyber are: 
        1.  Understand how to maximize revenue per mile, since this metric would provide a clearer view of into the revenue generation for comparing the different city types.
        2.  Evaluate areas underserved and recruit drivers in those areas, while promoting the service in those corresponding areas by going into lower granularity data and by zip code or neighborhood to better understand the current areas served and where to there are complentary areas.
        3.  Focus on highly populated areas since the probability of finding people, both riders and drivers, is greater.
        4.  The urban cities have a lower fares due to shorter lengths of haul, yet by focusing on profitability on those trips by pricing alligned to volume for short trips, while transitioning to a mileage based pricing model for a longer length trips.

## Resources
https://www.geeksforgeeks.org/different-ways-to-create-pandas-dataframe/