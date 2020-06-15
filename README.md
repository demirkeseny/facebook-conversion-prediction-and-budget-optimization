# Facebook Campaign Budget Optimizer

**Trello Board:** https://trello.com/b/46WSwmac/facebook-optimizer <br>
**Google Drive:** https://drive.google.com/drive/u/0/folders/1hptd9t5IOvPQc6XpH0EluX5Vj89N9erz

## Problem Statement
The companies usually spend a big portion of their marketing budget on social media campaigns. This is more convenient because the information is much easier to spread on a social media platform than doing it in a conference, company event or webinar. That's why utilizing social media as the main marketing tool will become more and more popular, which will increase the social media spendings. 

Unfortunately on social media, there is no linear relationship between the money you spent and conversions, likes or impressions you generate. Whether you get the return of your money completely depends on whether you are reaching out to the right audience on the right time with the right content. For instance the same amount of money spent on completely identical ads on Wednesday and Sunday might result in very different outcomes. 

Because of the above listed reasons, the companies who are active on social media **must** use an optimizer to have the highest return of investment. Without using a tool like this, it is very tough to navigate through these platforms. No matter how many years of marketing experience a marketing leader has, data needs to lead the way not the intuition.

## Objectives

The objective of this project is to build a model which can optimize the marketing budget on Facebook so that the maximum amount of conversions can be reached spending the least amount of money. The output of the model will be suggesting the users how much money to spend on which demographics. 

## Methodology
- Multinomial Logistic Regression
- Random Forest Classifier
- Support Vector Machine
- k-Nearest Neighbors
- XGBoost Classifier
- AdaBoost Classifier

## Constraints
Facebook Ads Manager forces the users to choose one from gender and location or time of the day. If the ad sets are downloaded with gender and location, the highest granularity obtained in the time field is day. If the users pick time of the day which provides hourly distribution of the conversions, the output won't include gender and location. Since gender and location were more important for the purpose of the project, day-of-the-week is included rather than the time.

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


