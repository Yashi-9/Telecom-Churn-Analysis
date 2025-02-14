# Telecom-Churn-Analysis
### Business Analytics Project (Power BI)
Dataset Info: Sample Data Set containing unbalanced Telco customer data and showing customers who left last month.

- What is Customer Churning ?

Customer churn (or customer attrition) refers to the loss of customers or subscribers for any reason at all.It is an industry-wide problem and a major contributor to EBITDA margin. 
A churned consumer boosts the market share of competitors and generates little to no money. If a customer leaves for a competitor, the service provider's acquisition costs would go up and purchasing a new customer cost a service provider much more than keeping an existing one.Therefore it is important to manage and learn about the reasons a customer might be churning.
### Introduction

Customer churn is a critical challenge for businesses striving for long-term growth. This report analyzes churn patterns, identifies key risk factors, and presents strategic recommendations. The goal is to provide actionable insights for the Marketing and Customer Helpline teams to enhance customer retention.

### Data Cleaning
1. Create a copy of base data.
2. There are some missing values in TotalCharges column however it is <1% compared to total dataset therefore it is safe to ignore them from further processing.
3. Grouped the tenure into bins of 12 months.

### Data Exploration

1. General Trends:

Higher Monthly Charges, Lower Tenure, Lower Total Charges,  No Online security, No Tech Support category also customers who opt for  Fibre Optics Internet service and Electronic checks are strongly linked to high churn.

2.Contract & Tenure Impact on Churn:

- High churn is prevalent in monthly contracts and lower tenures.

- Low churn is observed in long-term contracts (two-yearly contracts)  and customers engaged for more than five years.

3. Customer Demographics & Churn:

- Non-senior citizens exhibit higher churn rates.

- Customers without partners and dependents are more likely to unsubscribe.

- Gender has no significant impact on churn.

3. Service & Billing Factors

- Customers who lack online security, tech support, online backup, and device protection, and those who opt for paperless billing, exhibit higher churn rates.

- Fibre Optics Internet service, despite being the most popular and generating the highest total charges, also experiences high churn rates.

- Customers using Fibre Optics Internet service and electronic check payment methods despite being the most popular and generating the highest total charges, also experiences high churn rates.


- Tree map analysis indicates that most unsubscribed customers used both phone and internet services. Those who only used internet services relied primarily on DSL as their medium.
