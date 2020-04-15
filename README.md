# facebook-optimizer
Gunsu, you can take the datasets that are called 01_adset.csv until 04_adset.csv. Their numbers are changed!

## Deadline: 04/19/2020 5:00 pm

## Authors
- Gunsu Altindag | []() 
- Yalim Demirkesen | [linkedin.com/yalimdemirkesen](https://www.linkedin.com/in/yalimdemirkesen/)

## Problem Statement


## Objectives


## Methodology


## Constraints

## Materials
### Data 

|Document Name|Description|  
|-|-|
|combined_monthlytweets|state and handle combined tweets with the  corresponding queries|
|combined_tweet_outages|contains all info from combined_monthly_tweets plus ‘outage’ column, where 1 means the tweet occurred during a verified power outage|
|Grid_Disruption_00_14_standardized_clean|cleaned dataset of Grid_Disruption_00_14_standardized|
|monthlytweets_cleaned|cleaned dataset of monthlytweets|
|monthlytweets_cleaned_2|non-English characters removed|
|outages|includes power outage start & end time, respondent, geographic area, state, and number of customers affected|


### Notebooks

|Document Name|Description|  
|-|-|
|01_scrape_by_month|scraper to get a month of tweets at a time|
|02_clean_grid_disruption_00_14_standardized_data|cleaning the historical records about all the power outages in the last 15 years|
|03_preprocessing|cleaning the monthlytweets|
|04_tweet_source|understanding the source and the destination of the tweets|
|05_creating_network_outages|network diagram for the interactions between the users|
|06_outages_state_and_time|The first part of this notebook assigns location of power outages (as state abbreviations) to power outages. It then transforms event and restoration info to datetime values. The last adds a column to tweets data indicating if the tweet was at the same time as a verified outage.|
|07_frequency_charts|creating the frequency chart to understand the word usage from September 2009 until December 2012|
|08_tweet_vectorizer_clustering|running the logistic regression and k-means clustering models|



### Dashboard




## Implementation



## Future Developments





## References


