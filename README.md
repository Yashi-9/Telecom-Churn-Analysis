# Telecom-Churn-Analysis
### Business Analytics Project (Power BI)
Dataset Info: Sample Data Set containing unbalanced Telco customer data and showing customers who left last month.

What is Customer Churning ?

Customer churn (or customer attrition) refers to the loss of customers or subscribers for any reason at all.It is an industry-wide problem and a major contributor to EBITDA margin. 
A churned consumer boosts the market share of competitors and generates little to no money. If a customer leaves for a competitor, the service provider's acquisition costs would go up and purchasing a new customer cost a service provider much more than keeping an existing one.Therefore it is important to manage and learn about the reasons a customer might be churning.
### Introduction

Customer churn is a critical challenge for businesses striving for long-term growth. This report analyzes churn patterns, identifies key risk factors, and presents strategic recommendations. The goal is to provide actionable insights for the Marketing and Customer Helpline teams to enhance customer retention.

### Data Cleaning
1. Create a copy of base data.
2. There are some missing values in TotalCharges column however it is <1% compared to total dataset therefore it is safe to ignore them from further processing.
3. Grouped the tenure into bins of 12 months.

### Data Exploration
1. Total Charges increase as Monthly Charges increase - as expected.
2. Hence, all these 3 factors viz Higher Monthly Charge-has highest count of customers, Lower tenure and Lower Total Charge are linked to High Churn.
3. HIGH Churn seen in case of Month to month contracts
4. Non senior Citizens are high churners
5. No online security, No Tech support,No online backup,No Device protection and Yes Paperless billing have high churners
7.  Fibre Optics Internet-which attracts the most customers in internet service and is the highest in terms of total charges has high churners
8. LOW Churn is seens in case of Long term contracts-Two yearly, Subscription without internet service and The customers engaged for 5+ years
9. Electronic check medium are the highest churners-high customers are engaged.
10. Factors like Gender have no impact on churners.
11. From the tree map analysis, most unsubscribed customers used both phone and internet services. Those who did not have the phone services only used the DSN as the media of internet. The marketing department needs to upseți other internet methods to those who are not willing to take phone services
12. Customers without partners and dependents are observed to be more likely to unsubscribe from the companies services. This is also true for those with shorter contract periods. Ways to keep and entice these type of customers so that they can keep renewing their subscriptions should be evaluated and implemented for lower churn rate

1. Contract & Tenure Impact on Churn:

High churn is prevalent in month-to-month contracts.

Low churn is observed in long-term contracts (two-year contracts), subscription plans without internet service, and customers engaged for more than five years.

2. Customer Demographics & Churn

Non-senior citizens exhibit higher churn rates.

Customers without partners and dependents are more likely to unsubscribe.

Gender has no significant impact on churn.

3. Service & Billing Factors

Customers who lack online security, tech support, online backup, and device protection, and those who opt for paperless billing, exhibit higher churn rates.

Fibre Optics Internet service, despite being the most popular and generating the highest total charges, also experiences high churn rates.

Customers using electronic check payment methods show higher churn rates.

Tree map analysis indicates that most unsubscribed customers used both phone and internet services. Those who only used internet services relied primarily on DSL as their medium.
