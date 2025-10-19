# Project - Telecom Customer Churn Analysis

## Introduction

## Executive Summary

## Methodology & Dashboard Design
### Data Preparation
The first stage of the project focused on preparing the dataset for analysis. This involved a series of data cleaning steps to ensure consistency and accuracy, and address missing values, potential errors and structural issues within the data. The following steps were performed:
- Replaced blank text fields with 'N/A' and blank numeric fields with 0 to ensure consistency so that customer records were accurately represented (e.g customers without internet service previously showed blank values for columns such as 'Internet Type', 'Unlimited Data' etc.)
- Converted negative values to positive (e.g monthly charges incorrectly recorded as negative values) to maintain data accuracy
- Verified all CustomerID values were unique to ensure each record correctly represented an individual customer
- Confirmed no duplicate rows were present to prevent to ensure data accuracy and integrity

After completing this data preparation, the dataset was ready to start performing analysis with confidence that it is consistent and reliable.

### Exploratory Analysis
The exploratory analysis stage of the project started with uncovering key high-level churn insights. Pivot tables were created to find:
- The percentage of churned customers compared to retained customers
- The top 10 reasons customers said why they churned
- The distribution of churn categories among churned customers

Next, analysis moved onto evaluating potential churn drivers across services, demographics and behaviours. Factors such as contract type, customer tenure, monthly charge and age were investigated as potential key drivers. Service-focused analysis was also performed to identify if services such as streaming, device protection plan and tech support had an impact on churn.

As part of this data exploration, age group bands and tenure bands was added to the dataset to effectively evaluate if certain groupings influenced churn behaviour.

### Dashboard Build
Following the exploratory analysis, the next stage of the project focused on building an interactive dashboard. The purpose of the dashboard is to provide stakeholders with a high level view of the company's churn performance and its key drivers.

The dashboard was structured into three main sections; high level churn performance, churn behaviour drivers and service-based drivers. Selection of visualisations was based on the exploratory analysis where potential churn drivers that showed a meaningful impact on churn were included on the dashboard.

**High level churn performance**
This section provides a snapshot of overall customer churn with visualisations including:
- Overall Churn rate KPI card
- Churned vs Retained pie chart
- Top 10 Churn Reasons bar chart
- Churn Reason by Category pie chart

**Behaviour-based drivers**
This section highlights customer and account-related factors that were found to influence churn such as tenure, contract type, monthly charges and data usage. Visualisations included:
- Churn by Contract Type (bar chart)
- Churn by Monthly Charge (bar chart)
- Churn by Customer Tenure Group (bar chart)

**Service-related drivers**
This section highlights services and add-ons that showed an impact on churn. Visualisations included:
- Impact of Online Security on Churn (bar chart)
- Impact of Online Backup on Churn (bar chart)
- Impact of Device Protection Plan on Churn (bar chart)


## Insights
The Customer Churn Drivers Dashboard highlights several key findings and insights about customer churn. It gives a view of the overall churn performance, the main reasons customers report for leaving and factors that are influencing churn.

### High-level churn performance
The dashboard shows that the churn rate is 23.54%. The top reason that customers reported they have left is due to a competitor having better devices (20.70%), followed by the competitor making a better offer  (20.57%). This suggests that churn is strongly linked to competitor offerings, particularly around devices and pricing. This is further supported by 45% of churned customers falling under the 'Competitor'category for churn reasons.

14.55% of churned customers also reported they left due to the attitude of support person indicating that negative customer service interactions can turn customers away.

### Behavioural Drivers**
This section of the dashboard highlights customer and account-related factors that influence churn. It was found that contract type, length of tenure and pricing has a notabe impact on customer retention. These are the insights that emerged:

**Contract Type**
Customers on month-to-month contract are significantly more likely to churn (23.50%) compared to those on one-year (2.36%) or two-year contract (0.68%). 

**Customer Tenure**
The risk of churn is highest in the first 6 months of a customer's tenure (9.74%) and gradually decreases the longer a customer stays. 

**Monthly Charges**
Churn rates increase as monthly charges rise, from just 1.70% among customers paying $21-41 to 8.96% among those paying $81-101. The impact that pricing has on churn is supported by the 5.16% of churned customers who reported "price too high" as their reason for leaving.


Things to highlight:
- Churn rate
- Top reasons for churn
- Churn drivers - example people are more likely to churn in the first 6 months, people with month-to-month contract are likely to churn
- People that had services had a lower churn rate



## Recommendations
