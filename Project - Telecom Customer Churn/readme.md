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

The dashboard was structured into three main sections; high level churn performance, behaviour-based drivers and service-based drivers. Selection of visualisations was based on the exploratory analysis where potential churn drivers that actually showed to have an impact on churn were included on the dashboard. The following visualisations are included in the dashboard:

**High level churn performance**
- Overall Churn rate KPI card
- Churned vs Retained pie chart
- Top 10 Churn Reasons bar chart
- Churn Reason by Category pie chart

**Behaviour-based drivers**
- Churn by Contract Type bar chart
- Churn by Customer Tenure Group bar chart
- Churn by Monthly Charge bar chart
- Churn by Customer Monthly Data Usage bar chart

**Service-related drivers**
- Impact of Online Security on Churn bar chart
- Impact of Online Backup on Churn
- Device Protection Plan


## Insights

## Recommendations
