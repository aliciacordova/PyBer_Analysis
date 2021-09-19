# PyBer_Analysis

## Overview

Omar asked us to create an analysis in which we calculated the total trips by city type (Urban / Suburban and Rural), average rates for each city type, the total number of drivers for each city type and to understand how this data could be correlated.
To do this we had to created box-and-whisker plots to visualize the data and see if there are outliers for our trips, fares, and total drivers. We also created different pie charts and bubble charts, which allowed us to better understand the data in order to add it to the presentation and show it to the company, with the results of the analysis.


## Results


### Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

- In order to get the total rides, total drivers, total fares, the average fare per ride and the average fare per driver,  first we need to do some calculation for each one.   

![del1_summarydf](https://user-images.githubusercontent.com/87447639/133320878-15937d6f-59de-4159-8c36-081d42cf5008.PNG)
   
  
- Then with all the data previously calculated we create a pyber summary dataframe, for a better comparison between each city type:

![total_ city_ type](https://user-images.githubusercontent.com/87447639/133320706-f4fdcf55-d99d-4ffa-b7d7-5c7c1dfd9838.PNG)

- After we use the pivot() and resample() method we create a new data frame using loc method to analysed the data between 2019-01-01 through 2019-04-28. To obtanied the sum of fares for each week during that period.

![df_jan_april](https://user-images.githubusercontent.com/87447639/133320682-509e208a-011b-4f68-b1fd-598297c3fb5f.PNG)

- During the months of Data we analyzed the figures below shows % total fares, % total drivers and % total drives by City Type:

![Fig5](https://user-images.githubusercontent.com/87447639/133912916-84601f76-ced0-4be5-b4b4-e10bfb9d4c51.png)

![Fig6](https://user-images.githubusercontent.com/87447639/133912925-eb9a436a-1c19-4322-a544-51331cb07937.png)

![Fig7](https://user-images.githubusercontent.com/87447639/133912926-5b08baa2-4e57-4ad5-93bd-e043581fb5bc.png)

In summary we find the largest demand for riders is in urban cities compared to suburban and rural cities and the majority of the revenues were generated from urban cities.

- Finally we crate a multiple-line chart that shows the performances for to the sum of fares by week for each city type.  
   
![image](https://user-images.githubusercontent.com/87447639/133322666-3ae293e6-c9be-42ad-8daf-a9a173cc8aa4.png)


## Summary

After we help Omar, we can summarize theree business recomendations to the CEO for addressing any disparities among the city types.

- Decrease the number of drivers in the Suburban type, becasuse the diference beetweeen fare per ride and fare per driver is not worthy it. 
- Increase the number of rides in the Urban type (right now some drivers are not doing a single ride), because the average fare per ride is higger than the average fare per drivers. So you can collect more money.   
- The mayor peak of the sum of total fare for the Urban and Suburban types was in the week "2019-02-24", definetly we have to analize and take advantage if that was a especially holidays or event, so we can create in the future some promotions to increase more the demand in that week. 

