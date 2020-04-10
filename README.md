# PyBer_Analysis

## Challenge Overview
V. Isualize has tasked you with a new challenge: to create a new dataframe and a new mulitple-line graph. For this challenge you will need to:
- Create a dataframe showing the key metrics of the ride-sharing data by city type
- Create a multiple-line graph showing the total fares for each week by city type
- Summarize the data in the dataframe and multiple-line graph and explain their implications

## Challenge Summary

### Key Metrics by City Type
![challenge_summary.png](https://github.com/evanmgoodwin/PyBer_Analysis/blob/master/analysis/challenge_summary.png)

As we can see in the Key Metrics table above, there is an inverse correlation between the average fare and total rides by city type. In other words, while urban cities have the lowest average fare price, they have an exponentially larger amount of rides than the suburban and rural cities. We could assume that the fare prices in rural cities are higher due to supply-and-demand, however more data would be needed to confirm this. For example, if we had the average distance of each ride, we could determine if the rural fares were higher due to longer-distance rides, which would be more expensive. In summary, while rural cities return higher fare rates, expansion should be focused on urban cities, where the ride volume is so high that the profits would be the greatest.

### Weekly Average Fare by City Type
![ChallengeFig.png](https://github.com/evanmgoodwin/PyBer_Analysis/blob/master/analysis/ChallengeFig.png)

Looking at the above graph, we can see that weekly fare totals were generally consistent over the four-month time frame, with the exception of some spikes. Towards the end of February, for example, there was an increase in total fares across all city types. The urban cities had the largest variance of all types. That being said, urban cities are still by far the most profitable, with their lowest weekly fare total being greater than the highest weekly fare total of suburban cities. The suburban cities appear to be on an upward trend moving into May, though this might be another instance of a spike in total fares, and might very well decrease by the end of the month. A dataset covering a larger period of time, from January to December, is recommended for a more thorough anaylsis. A larger dataset would help in determining the upward and downward trend of all city types, and would be useful for forecasting the total fares for 2020.
