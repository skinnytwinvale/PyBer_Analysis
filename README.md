# PyBer_Analysis
## Overview of Project
PyBer CEO has given you and your manager a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. 

> Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

1. ***Deliverable 1***: A ride-sharing summary DataFrame by city type
2. ***Deliverable 2***: A multiple-line chart of total fares for each city type
3. ***Deliverable 3***: A written report for the PyBer analysis [`README.md`](https://github.com/emmanuelmartinezs/PyBer_Analysis). 

## Results

### Summary DataFrame

After merging two data sets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by city type. 

![Pic 1](https://github.com/Baylex/PyBer_Analysis/blob/main/Analysis/Deliverable1.PNG)

1. The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver.  The Urban drivers had the lowest average fare per ride and earned significantly less than the Rural drivers. 

2. The Rural city type had the least number of total drivers giving way to having the highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type.  

### Total Fare by City Type

From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks to show the total fares by city type.   

![Pic 2](https://github.com/Baylex/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

1. All three city types start to rise to a peak at the end for February.  For the Urban city type, that oscillating peak lasts through April, while the other city types wane in the month of March.  

2. The Rural city type increases again leading into the month of April.  The Suburban city type starts to peak again at the end of April, while the Rural city type drops off.   

## Summary 

1. A recommendation would recommend is include mileage distance data as part of the analysis process because the result of the summary Data Frame could be due to Urban cities being more compact and Rural cities being more spread out.

2. Pyber could also consider investing in more advertising. Because there is more total drivers then total drivers in Urban cities and this could potentially be due to the lack of awareness of Pyber in rural cities.

3. The big question could also be when is it more effective to launch the advertising if PyBer decided to invest more in advertising. AAfter reviewing the graph, the best time to launch is in Feburary because thats when theres an increase in fares. The advertising in Urban cities could potentially help out the other two city types.

3. 
