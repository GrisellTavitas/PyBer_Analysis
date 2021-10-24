# PyBer_Analysis
## Module 5
### Proyect Overview

Being a new employee as a data analyst at **PyBer, a ride-sharing app company**, I just received the work assignment of a lifetime: analize the rideshare data from January to the end of April of 2019, in order to create visualizations of this data for the CEO, V.Isualize.

Therefore, the objective of this assignment will be to help improve access to ride-sharing services and determine the affordability for underserved areas. So we receive a good advice from a partner as well: for the presentation of this analysis to the CEO, we will need to answer as far as possible, the questions that she may have, before she has the chance to ask them; and at the end we would be able to give more business recommendations to the CEO. 

### Resources

Data Source: 
  - city_data.csv
  - ride_data.csv
 
Software: Python 3.7.10 , jupyter notebook server 6.3.0

### Results: 

After merging the two data files that we had been provided, we were able to analize better the behavior for each type pf city, total rides per city type, the available drivers for each city type, and the sum of fares per type of city. Getting these following results:

![PyBer_summary_df](https://user-images.githubusercontent.com/90433064/138613548-fb819274-7686-41bc-9b77-f6270f261a90.png)

From the beggining we could notice in this next chart, that in the Rural areas, we might propouse some changes in the way the things are running right now, since we have less number of rides versus the other types of city and of course it's understandable that the less population we have in an area, the less ride's request we will have, but before to conclude that we must take a look as well on the offer that we're giving, the number of drivers in those neigborhoods is to low:

![Fig1](https://user-images.githubusercontent.com/90433064/138612729-ff82185c-5759-4843-93bb-aa24bb358489.png)
        
                      Where circle size correlates with driver count per city.

![PyBer_summary_df](https://user-images.githubusercontent.com/90433064/138610508-0fff5c97-2e3f-4a6c-88d1-ab9f882a5fa1.png)

It's good to have the big picture, but we must focus in the analysis for the period of time that the CEO requires: January to the end of April 2019; and see what happened during that time for each type of city. Since the CEO needs to have the results per week to this effect, we could visualize any trend or different behavior for each type of city.

![Fares_per_week](https://user-images.githubusercontent.com/90433064/138611063-2a9e7f46-1ed0-4652-8123-41c540160773.png)

![PyBer_fare_summary](https://user-images.githubusercontent.com/90433064/138611159-d2b729ac-3e4c-4fd7-9b3a-5578f0f1adcb.png)

So then, besides the conclusion that the offer affects directly the demand on the service, and the fares of the same. In this last graph, we could see that the tendency of the three types of city is quite consistent, there that doesn't mean that there are not differences between the results for each type. 

Based on the dates, we can see that the urban cities have their best performance during the last week of February and the begginig of March, which is coincident the part related to February in the case of the Suburban cities, but even when the rural cities also have a good performance during that week, is not its best one, having that the beggining of april would be when they have reached their peak.

### Summary: 
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
