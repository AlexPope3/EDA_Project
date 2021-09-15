Abstract:

The goal of this project was to help the WTWY optimize the placement of their street team in the MTA Subway system in order to maximize connections with individuals interested in attending their annual gala. I used Python and SQLAlchemy to analyze turnstile data provide by the Metropolitan Transportation Authority (MTA) website. My analysis included a timeseries analysis and data aggregation which produced useful insight as to where and when the organization should deploy their street team.

Design:

As a massive transportation hub running throughout city, the MTA Subway system would provide frequent and ample foot traffic of individuals who may be interested in the gala. Analzying Turnstile entry and exit data for the subway system is most the most practical way to identify traffic trends which will allow for the optimization of the WTWY street team. 

Data:

I used cumulative turnstile entry and exit data from May, April, and June of 2021. Each of the 377379 records of data from 379 unique subway stations represent entry and exits counts for each turnstile of the MTA subway system taken at four hour time intervals. 

Algorithms:

An exploratory data anaylsis was performed to gain insight into traffic trends. Firstly, only records within two standard deviations of the entry and exit means were included in the analysis. This was done as opposed to removing outliers because it was too difficult to differientiate those outliers from erroneous records. Data was sorted according to unique turnstiles so that duplicate entries could be removed. To enable deeper investingation, filters were added to display the weekday, datetime, and summation of entries and exits (traffic) for each turnstile. The summation was used to determine the busiest subway stations and the data was filtered further to find the heaviest tracker for each weekday and time of day; this played a key role in my recommendation. 

Tools:



Communication:
