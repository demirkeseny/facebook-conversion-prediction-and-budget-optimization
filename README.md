# channel-optimizer
Gunsu, you can take the datasets that are called 01_adset.csv until 04_adset.csv. Their numbers are changed!

## Deadline: 04/19/2020 5:00 pm

## Authors
- Gunsu Altindag | []() 
- Yalim Demirkesen | [linkedin.com/yalimdemirkesen](https://www.linkedin.com/in/yalimdemirkesen/)

## Problem Statement


## Objectives


## Methodology


## Constraints
Facebook Ads Manager forces the users to choose one from gender and location or time of the day. If the ad sets are downloaded with gender and location, the highest granularity obtained in the time field is day. If the users pick time of the day which provides hourly distribution of the conversions, the output won't include gender and location. Since gender and location were more important for our goals, we decided to include them instead of the time of the day.

## Materials
### Notebooks 

|Document Name|Description|  
|-|-|
|01_test_generator|Test data is created so that the target date range will be predicted.|
|02_predictor|The ensemble model predicts all the scenarios in the test data.|
|03_optimizer|The budget is optimized to return as much conversions as possible.|

### Data

Since the data is more than 25 MB, it is uploaded in 4 segments. The files are called: *01_adset.csv*, *02_adset.csv*, *03_adset.csv* and *04_adset.csv*. 

Before the upload, the actual numbers are changed. It is not a real data set and cannot be associated with any person/company/association. 



### Dashboard




## Implementation



## Future Developments





## References


