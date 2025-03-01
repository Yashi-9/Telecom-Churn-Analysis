# Telecom Customer Retention Analysis & Strategy| Power BI Dashboard
#### Dataset Info: Sample Data Set containing unbalanced Telco customer data and showing customers who left last month.

- What is Customer Churning ?

Customer churn (or customer attrition) refers to the loss of customers or subscribers for any reason at all.It is an industry-wide problem and a major contributor to EBITDA margin. 
A churned consumer boosts the market share of competitors and generates little to no money. If a customer leaves for a competitor, the service provider's acquisition costs would go up and purchasing a new customer cost a service provider much more than keeping an existing one.Therefore it is important to manage and learn about the reasons a customer might be churning.
## Introduction

Customer churn is a key driver of revenue loss in the telecom industry. This analysis identifies churn risk factors and recommends data-driven strategies to improve retention. Using Power BI, we provide actionable insights to optimize customer engagement and maximize lifetime value (LTV).

## Data Cleaning
1. Create a copy of base data.
2. There are some missing values in TotalCharges column however it is <1% compared to total dataset therefore it is safe to ignore them from further processing.
3. Grouped the tenure into bins of 12 months.

## Data Exploration

1. General Trends:

 Higher Monthly Charges,  Lower Tenure,  Lower Total Charges,   No Online security,  No Tech Support category , customers who opt for  Fibre Optics Internet service and Electronic checks are strongly linked to high churn.

2.Contract & Tenure Impact on Churn:

- High churn is prevalent in monthly contracts and lower tenures.

- Low churn is observed in long-term contracts (two-yearly contracts)  and customers engaged for more than five years.

3. Customer Demographics & Churn:

- Non-senior citizens exhibit higher churn rates.

- Customers without partners and dependents are more likely to unsubscribe.

- Gender has no significant impact on churn.

4. Service & Billing Factors

- Customers with incomplete service bundles (e.g., missing online security, tech support) and those on paperless billing are at higher churn risk, indicating a need for strategic upselling and customer 
  engagement initiatives.

- Fibre Optics Internet service, despite being the most popular and generating the highest total charges, also experiences high churn rates.

- Customers using electronic check payment methods also experiences high churn rates.


- Tree map analysis indicates that most unsubscribed customers used both phone and internet services. Those who only used internet services relied primarily on DSL as their medium.

## Recommendations

### 1. Data-Driven Retention Strategy

1.1. High-risk customers (month-to-month contracts, high monthly charges, short tenure):

- Offer contract discounts and loyalty rewards for shifting to long-term plans.

- Provide personalized service recommendations (e.g., tech support, online security) based on missing features in their subscription.

1.2 Customers using electronic checks:

- Incentivize them to switch to auto-pay options (credit card, direct bank transfers) with small discounts or exclusive perks.

### 2. Improving Customer Experience

2.1.Enhancing Customer Support & Proactive Interventions:

- Dedicated Retention Team: Assign customer success agents to engage with at-risk customers before they churn.

- Early Warning System: Trigger automated alerts when a high-risk customer shows disengagement (e.g., reduced usage, late payments).

- Personalized Outreach: Implement calls, emails, or SMS campaigns offering better service packages or tech support.

2.2. Service Bundling & Upselling

- Offer special promotions for customers using both phone and internet services, encouraging full-service adoption.

- Develop alternative internet solutions (e.g., fixed wireless, satellite) for customers reluctant to bundle phone services.

### 3. Customer Loyalty & Engagement Programs

3.1. Strengthening Long-Term Customer Relationships:

- Introduce a Loyalty Rewards Program offering benefits based on tenure, payment method, and contract type.

- Encourage community engagement by creating a Customer Referral Program with discounts for inviting new users.

- Provide an Exclusive Support Line for customers with long-term contracts, enhancing service value.

### 4. Monitoring & Continuous Improvement

4.1. Regularly Track & Analyze Churn Trends:

- Set up a real-time churn dashboard in Power BI or another analytics tool.

- Run monthly churn analysis to refine marketing and customer service interventions.

- Conduct customer surveys to gather feedback and adjust retention strategies accordingly.

## Final Thought
This analysis provides a data-driven roadmap for reducing churn and increasing customer lifetime value. Implementing these retention strategies can lead to measurable revenue growth and improved customer satisfaction. Explore the dashboard for deeper insights!"


#### Feel free to explore the project and share your feedback!




