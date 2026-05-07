# Project - Telecom Customer Churn Analysis

## Introduction
This project focuses on a fictional telecommunications company named TeleCo that are seeking to have a better understanding of customer churn behaviours and drivers. The aim of the project is to analyse customer churn data to uncover key factors influencing churn and identify opportunities to improve retention. 

An interactive dashboard was developed to visualise churn performance and its main drivers, enabling stakeholders to explore insights across customer demographics, service subscriptions and account characteristics. 

The findings of this analysis informed a set of actionable recommendations aimed to strengthen customer retention and enhance customer satisfaction.

## Executive Summary
TeleCo is a telecommunications company that want to understand the key drivers of customer churn with the aim to improve retention. Customer churn data was analysed to uncover churn patterns and an interactive dashboard was developed for TeleCo's senior stakeholders to visualise key insights.

The analysis revealed an overall churn rate of 26.54%, primarily driven by better competitor offerings and pricing, followed by poor customer service. Month-to-month contracts and higher monthly charges were found to correlate with churn. It was also identified that customers who were in their first 6 months with TeleCo were at higher risk of churning. In contrast, customers who signed up for add-on services such as online security, online backup or device protection showed lower churn rates.

Based on these findings, several recommendations have been proposed:
- Strengthening early engagement
- Encouraging longer-term contracts
- Reviewing pricing structures
- Uplifting customer service experience
- Promoting add-on services
- Maintaining market competitiveness

Following these recommendations should translate to reduced customer churn and improved customer satisfaction within TeleCo.

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
Following the exploratory analysis, the next stage of the project focused on building an interactive dashboard. The purpose of the dashboard is to provide TeleCo's senior stakeholders with a high level view of the company's churn performance and its key drivers.

The dashboard was structured into three main sections; high level churn performance, churn behaviour drivers and service-based drivers. Selection of visualisations was based on the exploratory analysis where potential churn drivers showed a meaningful impact on churn were included on the dashboard.

#### High level churn performance
This section provides a snapshot of overall customer churn with visualisations including:
- Overall Churn rate KPI card
- Churned vs Retained pie chart
- Top 10 Churn Reasons bar chart
- Churn Reason by Category pie chart

<img width="676" height="416" alt="image" src="https://github.com/user-attachments/assets/7c3cd71e-fef3-4427-9666-c61fc5653dbb" />


#### Behaviour-based drivers**
This section highlights customer and account-related factors that were found to influence churn such as tenure, contract type, monthly charges and data usage. Visualisations included:
- Churn by Contract Type (bar chart)
- Churn by Monthly Charge (bar chart)
- Churn by Customer Tenure Group (bar chart)

  <img width="544" height="410" alt="image" src="https://github.com/user-attachments/assets/05b9e357-1eaf-420a-b9c4-581e13847a23" />


#### Service-related drivers
This section highlights services and add-ons that showed an impact on churn. Visualisations included:
- Impact of Online Security on Churn (bar chart)
- Impact of Online Backup on Churn (bar chart)
- Impact of Device Protection Plan on Churn (bar chart)

<img width="542" height="398" alt="image" src="https://github.com/user-attachments/assets/d5a576e2-0209-45f9-a14d-aefbe4decd06" />


## Insights
The Customer Churn Drivers Dashboard highlights several key findings and insights about customer churn. It gives a view of the overall churn performance, the main reasons customers report for leaving and factors that are influencing churn.

### High-level churn performance
The dashboard shows that the churn rate is 26.54%. The top reason that customers reported they have left is due to a competitor having better devices (20.70%), followed by the competitor making a better offer  (20.57%). This suggests that churn is strongly linked to competitor offerings, particularly around devices and pricing. This is further supported by 45% of churned customers falling under the 'Competitor'category for churn reasons.

14.55% of churned customers also reported they left due to the attitude of support person indicating that negative customer service interactions can turn customers away.

### Behavioural Drivers
This section of the dashboard highlights customer and account-related factors that influence churn. It was found that contract type, length of tenure and pricing has a notabe impact on customer retention. These are the insights that emerged:

**Contract Type**
Customers on month-to-month contract are significantly more likely to churn (23.50%) compared to those on one-year (2.36%) or two-year contract (0.68%). 

**Customer Tenure**
The risk of churn is highest in the first 6 months of a customer's tenure (9.74%) and gradually decreases the longer a customer stays. 

**Monthly Charges**
Churn rates increase as monthly charges rise, from a 1.70% churn rate among customers paying $21-41 to an 8.96% churn rate among those paying $81-101. The impact that pricing has on churn is supported by the 5.16% of churned customers who reported "price too high" as their reason for leaving.

### Service-related Drivers ###
This section of the dashboard explores how service add-ons impact customer retention. The analysis found that customers who sign up to additional services such as online security, online backup or device protection are less likely to churn. This indicates that these services enhance customer experience and satisfaction, contributing to stronger loyalty to the organisation.

**Online Security**
Customers with online security only had a churn rate of 5.35%, compared to 26.48% among those without it. 

**Online Backup**
Customers with online backup also show a lower churn rate (9.48%) than those without it (22.35%)

**Device Protection Plan**
Customers who have a device protection plan churn at a lower rate (9.88%) than those without (21.95%).

## Recommendations ##
This analysis highlighted the key drivers that influence customer churn. As a result, several opportunities were identified to strengthen retention and improve the overall customer experience. The following recommendations outline potential actions to address these drivers and build stronger customer loyalty. 

**1. Strengthen Early Engagement**
It was found that customers are most likely to leave within their first six months. Introducing proactive engagement initiatives such as onboarding programs, early satisfaction surveys and personalised offers can help build trust and satisfaction during this critical period.

**2. Encourage Longer-Term Contracts**
Customers on a month-to-month contract were found to have significant higher rates of churn compared to those in longer-term contracts. Encouraging longer-term commitments through loyalty reward, discounts and exclusive benefits could help reduce churn and improve customer stability.

**3. Review Pricing and Value Perception**
Higher monthly charges were linked to higher churn rates, with some customers citing "price too high" as their reason for leaving. This could be addressed by reviewing pricing structures, offering flexible payment options or introducing bundled plans to enhance perceived value.

**4. Enhance Customer Service Experience**
Poor service interactions was one of the top reasons customers cited as their reason for leaving. Uplifting frontline training, improving resolution times and tracking customer satisfaction metrics can help enhance service quality.

**5. Promote Service Add-ons**
Customers who subscribed to online sercurity, online backup or device protection services had significantly lower churn rates than those without those add-ons. Promoting these services should be prioritised which could include providing bundled plans, cross-selling or increasing awareness through marketing campaigns.

**6. Stay Competitor with Market Offers**
Competitor-related churn was found to be a key driver, particularly around better devices and prices being offered by a competitor. Conducting regular competitor benchmarking and reviewing product offerings and pricing will be important to keep the organisation competitive and responsive to the market.

These are the recommendations based on the analysis performed on TeleCo's churn data. As next steps, TeleCo should assess which recommendations should prioritised in the short term and which will require longer term strategic planning.

