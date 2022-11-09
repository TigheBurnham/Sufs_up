# Sufs_up

## Overview of the analysis: 

The stakeholder for this project W. Avy liked the previous analysis so he requested the temperature trends in Oahu for the months June and December. W. Avy requested these two months in order to determine if the surf and ice cream shop business was also sustainable year-round.

## Results: 

Below the project utilized Python, Pandas, and SQLAlchemy to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve temperatures for the month of June and December. These temperatures were then converted to a DataFrame in order to generate the summary statistics.

![list_to_dataframe](https://user-images.githubusercontent.com/112028534/200719765-24260bec-3de0-4920-98cd-cce209cd6954.PNG)

### Deliverable 1: Determine the Summary Statistics for June

![june_summary_stats](https://user-images.githubusercontent.com/112028534/200717265-ef423034-f6a8-438c-8da4-5c7ea5b3f638.PNG)

### Deliverable 2: Determine the Summary Statistics for December

![december_summary_stats](https://user-images.githubusercontent.com/112028534/200717258-59f37304-f9e8-42d4-84f5-a67e9a61cfe2.PNG)

- From the summary statistics we can see the average temp in June was 75 and the average temp in December was 71. Therefore, there is only a 4 degree average temperature difference between the two months.

- The lowest temperature in June was 64 and the lowest temp in December was 56. This leaves a 8 degree difference in the lowest temps during the specified months. The highest temps were only 3 degrees different.

- Based on the max temperatures, the min temps, and the average temperatures there appears to only be a small temperature difference between the two months.

## Summary: 

In conclusion, we can see there is not much of a temperature fluctuation when comparing the summer month of June to the winter month of December. Therefore, based on the year round climate stability it would appear this would not play a role in changing the demand for the new surf and ice cream shop. 

The two additional queries that could be performed would be to gather the precipitation data for the month June and for the month of December. With this additional information we could see if there is a rainy and dry season for Oahu and plan hours for the surf and ice cream shop accordingly. 
