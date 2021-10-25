# PyBer_Analysis_Mod5

## Overview/Purpose
The purpose of the Module 5 Challenge was to create a summary DataFrame of the ride-sharing data by city type using Pandas and the Python knowledge acquired thus far.  Additionally, a chart was assigned to show the weekly fares for each city type, using Pandas and Matplotlib, along with a written report summarizing the differences in the data related to city type.    

 
## Results 
In order to create our summary DataFrame, several calculations had to be created based on the datas sets city data, ride share data, and the merged data city/ride share data.  The calculations created are below:

  1.  Total rides for each city type (using the merged data)
  2.  Total drivers for each city type (city data only was used for this calculation)
  3.  Total fare amounts for each city type (using the merged data)
  4.  Average fare per ride by city type (total fares divided by the total rides)
  5.  Average fare per driver by city type (total fares divided by the total drivers)

Once these were completed, the summary DataFrame was created and formatted:
![image](https://user-images.githubusercontent.com/90434559/138618929-b3770d6d-6a9e-498b-a9c6-cc2d112ed70f.png)

The summary DataFrame highlighted that rural city types had far fewer total rides, total fares, total drivers, higher average fares per ride, and higher average fares per driver.  Conversely, urban city types had a far greater total rides, total drivers, and total fares.  Also, because the total rides and total drivers were so much greater, this brought down the average far per ride and the average fare per driver.  

Once the data was pivoted to look at a per week view by month, the chart below was created and the differences between the urban and rural city types is much more visable.
![image](https://user-images.githubusercontent.com/90434559/138619193-c9d4dc3f-2ebc-4118-8bdc-46fff270e585.png)


## Summary
Based on the analysis, the revenue generation in rural areas is far below that of urban areas.  This is based on the lower number of total rides in the rural areas.  Without additional research and analysis, it cannot be determined absolutely whether there are fewer rides because the fares are higher per ride or if there is simply less demand (most likely less demand, however).  In order to address the dispartities in city types, below are three recommendations:
  1.  Decrease the fare price in the rural areas to test if total rides increase
  2.  Increase the fare price in the urban areas in order to generate increased total fare revenue
  3.  Decrease the fare price in suburban areas, minimally, to possibly generate additional total rides



