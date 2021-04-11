# PyBer_Analysis

## Overview of the analysis

V. Isualize has asked for a summary of ride-sharing data by city type (urban, suburban, and rural). He has asked to create a summary DataFrame and would like the data visualized as a multiple-line graph that sows the total weekly fares for each of the city types. He would also like a written interpretation of the data which includes how the data differs by city and how the differences can be used by decision makers.

## Results
The data showed a few interesting trends that were not initally expected. 

- Avg. Fare per Ride was most expensive for Rural cities ($34.62) followed by Suburban ($30.97) and then Urban ($24.53).
- Average Fare per driver was the highest for Rural cities ($55.49) followed by Suburban ($39.50) and then Urban ($16.67)
- Urban cities total over one thousand rides (1,625) and was more than double Surburban (626) and 10x the number of rides as Rural (125)

![image](https://github.com/jb-ut/PyBer_Analysis/blob/main/analysis/PyBer_table_ssummary.png)

Looking at monthly trends for total fares Rural cities seemed to be the least volatile of city types. Total fares for Urban cities flucuated quite a bit from the end of Feb 2019 to April 2019. Suburban cities had a very sharp drop-off at the tail end of Feb 2019 and while other city types also saw a decline in this period it was most pronounced for Suburban cities. 

![image](https://github.com/jb-ut/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)

## Summary
1. Because fares for rural city types are have the highest Average Fare per Ride the company could potentially try to add more drivers to rural areas to increase total fares. There may be a low threshold for adding drivers given that demand may be low in rural areas.

2. The sharp drop in total fares in suburban areas at the end of February should be reviewed as the it dropped more severely than other city types. This would be down in the hopes of preventing another sharp drop in 2020.

3. The company could experiment with raising fare prices in Urban areas given that demand will likely always be high. This could be a way to maximize profits.
