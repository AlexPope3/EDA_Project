Abstract:

The goal of this project was to help the WTWY optimize the placement of their street team in the MTA Subway system in order to maximize connections with individuals interested in attending their annual gala. I used Python and SQLAlchemy to analyze turnstile data provide by the Metropolitan Transportation Authority (MTA) website. My analysis included a timeseries analysis and data aggregation which produced useful insight as to where and when the organization should deploy their street team.

Design:

As a massive transportation hub running throughout city, the MTA Subway system would provide frequent and ample foot traffic of individuals who may be interested in the gala. Analzying Turnstile entry and exit data for the subway system is most the most practical way to identify traffic trends which will allow for the optimization of the WTWY street team. The focus of the analysis was on the first five stations that had total entry counts greater than the median. These stations were selected to help eleminate unexplained outliers and it was impractical to target the largest crowds in stations with the highest entry counts. 

Data:

I used cumulative turnstile entry and exit data from May, April, and June of 2021. Each of the 377,379 records of data from 379 unique subway stations represent entry and exits counts for each turnstile of the MTA subway system taken at four hour time intervals. 

Algorithms:

An exploratory data anaylsis was performed to gain insight into traffic trends. Data was sorted according to unique turnstiles so that duplicate entries could be removed. This as performed to avoid possibly skewing the total entry count for each station. To enable deeper investingation, filters were added to display the weekday, datetime, and summation of entries and exits (traffic) for each turnstile. The summation was used to determine the busiest subway stations and the data was filtered further to find the gfor each weekday and time of day; this played a key role in my recommendation. 

Tools:

-Pandas and SQLAlchemy for data manipulation
-MatPlotLib for data visualization and presentation 


Communication:
