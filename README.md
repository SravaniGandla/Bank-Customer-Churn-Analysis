
# Bank Churn Analysis Using Power BI: A Step-by-Step Insight

## Project Overview

1.	The aim of this project is to analyze bank customer data to identify the factors contributing to customer churn using Power BI, SQL, and Excel.
2.	To gather valuable insights from the analysis to understand patterns, trends, and correlations associated with bank customer data.
3.	To provide recommendations to the bank to mitigate churn. It allows banks to address customer needs, improve retention strategies, and save costs associated with acquiring new customers. Identifying at-risk customers allows banks to implement personalized retention strategies, improving customer experience, and reducing attrition rates.

## Problem statement

The bank is facing a significant challenge with high churn rates and aims to reduce costs linked to customer acquisition. Understanding the reasons behind customer churn is pivotal for tailoring services and implementing targeted retention efforts. This allows the bank to address customer needs, refine retention strategies, and identify at-risk customers for personalized retention strategies.


### Data Source

Domain: Banking Domain
Dataset Name: Bank_Churn.csv, ActiveCustomer.xlsx, CreditCard.xlsx, CustomerInfo.csv, ExitCustomer.xlsx, Gender.xlsx, Geography.xlsx

Dataset Type: Excel and CSV Datatypes

Dataset Size: 10,000 customers' data spanning 4 years.


### Data Cleaning/Preparation
- Step 1 :Checked for presence of duplicates and eliminated them.
- Step 2 :Removing irrelevant columns which does not associated with customer churn.
- Step 3 :Data type standardization.
- Step 4 :Formatting dates for consistency.
- Step 5 :Formatted numerical data for consistency.
- Step 6 :Handling the text values and removed special characters in name.
- Step 7 :Handled null values.

https://github.com/SravaniGandla/Bank-Customer-Churn-Analysis/issues/1#issue-3296548868 - Snapshot of Report

https://github.com/SravaniGandla/Bank-Customer-Churn-Analysis/issues/2#issue-3296569001

## Inferences from the analysis:

1. Total customers associated with the bank are 10,000.
2. Churn Rate is 20.41%. Which is higher than the healthy range, churn rate of 5-7% annually is considered average in the banking industry. So the bank should consider this as a serious problem and take necessary actions.
3. Retention Rate 79.63%. High retention rate indicates customer satisfaction and loyalty. Anything above 90% might be considered healthy.
4. Active Customer Rate 51.51%. Desired range for active customer rate is above 70-80%. These desired ranges can vary based on the bank's services and customer engagement strategies. Inactive Customers have a higher churn rate.
5. Credit Card Holder Rate is 70.55%. Bank is doing good in this case. Typically, a rate higher than 50-60% might be considered good, but this can vary widely. But, churn rate is high in case of the credit card holders. People with fair and poor credit score are leaving the bank.
6. Average Tenure is 5 Years, Indicating the level of loyalty and the bank's ability to retain its customer base. Most of the customers are leaving the bank within 4 to 5 years.
7. Churn Rate is minimum in Year 2016 that is 16.67% and maximum in year 2017 that is 21.45%. Also, we have forecasted the Churn rate for the next four quarters predicting churn rate between lower bound 15 or 16% and the upper bound is 24 to 25% with a 95% confidence level.
8. Churn Rate is highest in Germany that is 32.44% and for both France and Spain churn rate is around 16%.

## Recommendations:
1. Enhance customer service, resolving customers' issues, offer personalized experiences to increase satisfaction.
2. Implement loyalty programs, rewards for long-term customers to reduce churn.
3. Regularly engage with customers via multiple channels, offering relevant updates and personalized offers.
4. Collect and act on customer feedback to address pain points and enhance overall satisfaction
5. Encourage active participation in banking activities, offer exclusive benefits, and personalize services based on customer behavior.
6. Upselling and Cross-Selling; Train staff to recommend complementary products or services to existing customers based on their profiles and behavior.

## Customer Segmentation:
 Segment customers based on behavior and preferences, offering tailored packages to each segment. Like
