# Surfs Up Challenge

# Overview
## Purpose
The purpose of the analysis is to understand the weather trends in Oahu, HI for the client to understand the annual viability of a surf shop and ice cream business. The client is concerned due to historical experience where a previous investment failed. To provide better insight, we will be providing statistical analysis on the weather in Oahu to help mitigate and alleviate concerns. 

# Analysis
## Resources
We will be utilizing SQLite database, with a SQLalchemy to query the relevant data points for the analysis. 

We utilized ORM, create engine function, and automap base function. We then reflect tables using the prepare function and session link to 

# Results
## Summary
* The average temperature in December was 71 degrees and June was 74.9 degrees. 
* The low for December was 56 degrees and for June was 64 degrees. 
* The high for December 83 degrees and for June was 85 degrees. 

![Summary_Statistics](https://user-images.githubusercontent.com/115019829/206601198-c952b32e-5352-492e-8afa-41028d08604a.png)



## Additional Queries

Additional queries that would gather more weather data for June and December would be precipitation in June and December. 

* June precipitation was 14%. 

![June_Summary_Precip](https://user-images.githubusercontent.com/115019829/206601159-ba76921e-c0f5-4e5c-a627-cd94d5654325.png)


* December precipitation was 22%.

![December_Summary_Precip](https://user-images.githubusercontent.com/115019829/206601135-3f70b838-2d51-4659-8060-54b4def33faf.png)
