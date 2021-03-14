# Bikesharing

Columbia Data Science Module 14

## Bikesharing Overview
In this project, I have created a series of data visualizations in anticipation of a pitch meeting; we are going to propose a bikesharing system for Des Moines that operates similarly to the Citi Bike system in New York City. Fortunately, Citi has made the ride data publicly available [here:](https://www.citibikenyc.com/system-data)

For this project, I have used data from August 2019. I aim to answer the following questions: 
1) How long do trips typcically last? 
2) How does use behavior vary between men and women? 
3) What times are Citi Bikes most heavily used? 
4) Where are Citi Bikes used most often? 
5) How evenly are rides distributed across the bike fleet? 


## Resources
Data source: election_results.csv

Software: Jupyter Notebook, Python 3.8.6, Tableau Public 2020.4

## Results

The overwhelming majority of trips last less than an hour, and many last less than 15 minutes.
![Story1](Resources/Story1.png)

Men constitute the majority of riders - all genders have similar behavior in terms of checkout times.
![Story2](Resources/Story2.png)

There is a clear pattern: the heaviest bike use occurs during weekdays during the commute to and from work. On weekends, bike usage is more evenly distributed throughout the day. 
![Story3](Resources/Story3.png)

Men and women have similar bike-use habits throughout the week, women just use the service less than men in general.
![Story4](Resources/Story4.png)

It appears subscribers of all genders use Citi bikes primarily for commuting, as their heaviest usage is on weekdays. Meanwhile, customers of all genders use Citi bikes most heavily on weekends. This implies that residents are the primary subscriber base and tourists are the primary customer base.
![Story5](Resources/Story5.png)

The highest number of users is clustered in Manhattan, particularly in the areas with the highest population density and tourist traffic. There were 2,344,224 total rides in NYC in August, 2019. If we assume ridership is directly proportional to population, we could expect August ridership of 5,523 for Des Moines.
![Story6](Resources/Story6.png)


The number of rides per unique bike vary wildly; usage per bike will need to be monitored to allocate greater maintenance to bikes that are used more frequently.
![Story7](Resources/Story7.png)
