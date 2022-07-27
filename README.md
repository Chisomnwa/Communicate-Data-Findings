# Telecom Customer Churn Data Exploration

## by Nnamani Chisom Promise

## Dataset

This dataset contains 3333 rows representing each customer, with 11 features or variables.

8 of the features which include (account_weeks, data_usage, customer_service_calls, day_mins, day_calls, monthly_charge, overage_fee. roam_mins) are numerical data types, while the other 3 which are (churn, contract_renewal, and data plan) are in categorical data type.

This dataset was sourced from Kaggle and can be obtained via this [link](https://www.kaggle.com/datasets/barun2104/telecom-churn)

## Metadata


 - **Churn:** 1 if customer cancelled service, 0 if not
 
 
 - **AccountWeeks:** number of weeks customer has had active account
 
 
 - **ContractRenewal:** 1 if customer recently renewed contract, 0 if not
 
 
 - **DataPlan:** 1 if customer has data plan, 0 if not
 

 - **DataUsage:** gigabytes of monthly data usage
 

 - **CustServCalls:** number of calls into customer service
 

 - **DayMins:** average daytime minutes per month
 

 - **DayCalls:** average number of daytime calls
 

 - **MonthlyCharge:** average monthly bill
 

 - **OverageFee:** largest overage fee in last 12 months
 

 - **RoamMins:** average number of roaming minutes
 
 I changed all the column names to lowercase and used underscore to seperate athe column names that were made up of more than two words. This was done for easy accessing of the columns when coding.

I changed the  data type of Churn, Contract renewal and Data plan to cataegorical data types.

## Summary of Findings


In the exploration, I found that data plan and contract renewal feature helped more in predicting if the customers will stay with the company or not.

Via a heatmap between churn and data plan, I found out that more customers who had no data plan were lost by the company.
about 80(8.5%) of their customers who had data plans were still lost by the company. But a higher percentage of 403(16.7%) who did not have data plan were lost by the company.

I also found out that with some of the customers having no data plan, it resulted to most of them having 0 data usage. A boxplot was used to visualize this and it showed a linear relationship between data plan and data usage.

There is also a positive relationship between the average daytime minutes per month and the monthly charge. Here we can additionally observe one surprising fact. Almost all customers with a monthly charge between 60 and 80 and average daytime minutes per month above 200 left the company.

It was surprising to find out that the customers who have data plan with high data usage later decided to quit the company services. Why? It might be that the monthly charge for the particular data plan they were on was quiet high. So I suggested that maybe a friendly data plan can help make them stay with the company.

## Key Insights for Presentation

For the presentation, I focus on the influence of influence of categorical variables (data plan and contract renewal) and how numeric features (data usage, monthly charge, and customer service calls) predict customer churn.

I start by introducing the distribution of each of these variables, with Churn and the other two categorical variables leading.

Afterwards, I then introduced how Data plan and Contract renewal predicts customer churn. I also looked at how data plan and contract renewal correlates with each other using a heatmap.

Then because churn is the tarhet variable, I looked at how other features that I already mentioned above that I would be focusing on affects customer churn.
