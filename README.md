# PyBer_Analysis!

## Goals
PyBer ridesharing company has provided us with their ridership data. The objective of this study is to compare the total driver count, the average fare per trip, and the average fare per driver for three different city types (urban, sub-urban, and rural).  


## Results: 
Pandas and Matplotlib liberaries were imported to retrieve and process data from the source csv files.
Summary dataframe is shown below:

[Summary DataFrame](https://user-images.githubusercontent.com/82549848/120165197-eda7a280-c1c0-11eb-8fca-62c071536d71.PNG)

It can be observed that there were total of 2405 drivers in the urban setting, while there were only 490 drivers in sub-urban, and 78 in rural environments. 

It's also notable that the average trip fare in rural setting is $34.62, which is slightly higher than $30.97 for sub-urban, and considerably higher than $24.53 paid for an average urban trip.

Furthermore, there appears to be a significant gap in the "average fare per driver" for various city types. A rural-area driver makes an average of $55.49 per trip, while an urban-area driver makes only $16.57 per trip.
 
Total weekly fare trends were plotted for the first 4 months of 2019. This plot suggests that sub-urban and urban trips account for over 90% of the total generated revenue. Weekly revenue generation did not appear to change significantly from Jan to April 2019. 

[Plot 1](https://user-images.githubusercontent.com/82549848/120167196-0f098e00-c1c3-11eb-95d1-c407a8650ab8.png)


## Recommendations: 
The service coverage/availability appears to be disproportionate in various regions. This can contribute to a higher demand to supply ratio and subsequently drive up the fare. As a shortage of driver is observable in rural areas (See [Summary DataFrame](https://user-images.githubusercontent.com/82549848/120165197-eda7a280-c1c0-11eb-8fca-62c071536d71.PNG)) , it's recommended to assign more drivers to these regions in order to balance the supply and demand and to reduce the average cost per trip. 

