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


In the exploration, I found out that Data plan and Monthly charges features helped more in predicting if the customers will stay with the company or leave.

Via a heatmap between churn and data plan, I found out that more of the customers had no data plan and were lost by the company. About 80(8.5%) of the customers had data plans but were still lost by the company. But a higher percentage of 403(16.7%) who did not have data plan left the company.

Then when more customers have no data plan, it leads to them not using data from the company and will eventually make them not to renew their contracts. But, I found out that what's making them to have no data plan is high monthly charges. So the data plan isn't friendly, and I strongly suggested this should be looked into.

Friendly data plans are going to make the customers buy and use more data, and it will eventually make the renew their data plans.

Customer churn is also affected by Customer service calls. I noticed that the customers who made more than two customer service calls didn't recently renew their contracts. It could be that their concerns wasn't addresses in those calls or maybe it took more time for their issues to be resolved. To conclude this, I will need more data like how much time each customer spent on those calls, and if their issue was resolved after making up two two calls or not.

I did suggest that immediate improvementshould be made in the quality of customer service that are being provided to the customers and the company should make sure that their issues are resolved within 1 to 2 calls.

