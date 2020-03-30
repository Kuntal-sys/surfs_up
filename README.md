# surfs_up

- Performing data analysis and data exploration on a weather dataset,

- Using SQLalchemy to query and create engine of connecting SQLite and python pandas.

- Designing a Flask application to showcase a dynamic data analysis.



# Challenge

Seasonal weather analysis for Oahu island based on a comparison of precipitation and temperature between June and December from 2010 to 2017 across all observation stations.

## Project Process:

- **Determine key statistical data about the month of June.**
![Jane_stats_summary.png](/Analysis/June_stats_summary.png)
- **Determine key statistical data about the month of December.**
![Dec_stats_summary.png](/Analysis/Dec_stats_summary.png)
- **Compare your findings between the month of July and December.**

*Based on a comparison of precipitation and temperature between June and December from 2010 to 2017 across all observation stations, it’s possible to notice the following statistical information:*

 1. Over 7 years,during June there are 1574 precipitations occurred and 1700 temperatures  observed, pose to December where higher than 1405 precipitations and 1517 temperatures  observed. 
 2. The difference 183 i.e (1700-1517)  between two observations counts indicates that data of December 2017 is not included.
 - Comparing precipitation data i.e mean (0.217) and median (0.03) from December are higher than June month's mean (0.136) and median (0.02).
 - Precipitation derivative indicators for December also had higher SD and Maximum precipitation. 
 - During December,SD (0.541) is higher than June SD (0.336). 
 - The minimum SD for December and June are zero
 - December SD max (6.42) is higher than June SD max(4.43).
 - Comparing temperatures,indicates that June temperature are higher than December.

- ** Recommendations for further analysis.**

 1.The lack of data from December 2017  may cause less reliable of data. The database should generate more recently winter data to compare summer and winter precipitation.
 