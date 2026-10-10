# FUTURE_DS_02
Customer Churn and Retention Analysis
1. Executive Summary
This analysis examines customer churn and retention patterns using a telecommunications customer dataset containing 7,043 customers. The objective was to identify customer segments associated with higher churn, understand customer lifetime patterns, and provide data-driven recommendations to improve customer retention.
The overall churn rate was 26.54%, with 1,869 customers classified as churned and 5,174 retained. The analysis identified customer tenure, contract type, internet service, payment method and other customer characteristics as important variables associated with differences in observed churn rates.
The strongest pattern was observed across customer tenure. Customers with 0–3 months of tenure had a 56.2% churn rate, compared with only 6.6% among customers with 61–72 months of tenure. Month-to-month customers also had substantially higher churn than customers on longer-term contracts.
These findings suggest that the business should place particular emphasis on early-stage customer engagement, contract retention strategies, service experience and targeted monitoring of high-risk customer segments.

2. Business Objective
The purpose of this analysis was to answer the following business questions:
•	What is the overall customer churn rate?
•	Which customer segments are most associated with churn?
•	How long do customers typically remain active?
•	Which customer lifecycle stages have the highest churn?
•	Which factors should the business investigate as potential retention drivers?
•	What actions could improve customer retention?

3. Data Preparation
The dataset contains 7,043 customer records and 21 variables covering demographic characteristics, services, contract information, payment methods, tenure, monthly charges, total charges and churn status.
Data preparation included:
•	Reviewing the dataset structure and data types.
•	Converting the TotalCharges field from text to numeric format.
•	Checking for missing values.
•	Creating a binary churn indicator for analysis.
•	Creating customer tenure bands to analyse lifecycle patterns.
•	Grouping customers by contract, internet service, payment method and other characteristics.

4. Key Performance Indicators
Metric	Result
Total customers	7,043
Churned customers	1,869
Retained customers	5,174
Churn rate	26.54%
Retention rate	73.46%
Average customer tenure	32.4 months
Median customer tenure	29 months

5. Churn and Customer Lifetime
Customer tenure was strongly associated with observed churn.
Customers with shorter tenure had substantially higher churn rates than long-term customers.
Tenure	Churn Rate
0–3 months	56.2%
4–6 months	44.6%
7–12 months	35.9%
13–24 months	28.7%
25–36 months	21.6%
37–48 months	19.0%
49–60 months	14.4%
61–72 months	6.6%
The average tenure of churned customers was approximately 18 months, compared with approximately 38 months among retained customers.
This indicates that the early customer lifecycle represents an important period for retention efforts.

6. Contract Analysis
Contract type showed substantial differences in observed churn.
Contract	Churn Rate
Month-to-month	42.7%
One year	11.3%
Two year	2.8%
Customers on month-to-month contracts had the highest churn rate. Customers on two-year contracts had the lowest observed churn rate.
The analysis identifies a strong association between contract type and churn, although it does not establish that contract type itself causes customers to leave.

7. Internet Service Analysis
Internet service also showed substantial differences in churn.
Internet Service	Churn Rate
Fiber optic	41.9%
DSL	19.0%
No internet service	7.4%
The relatively high churn rate among fiber-optic customers warrants further investigation into service quality, pricing, customer expectations, technical support and competitive conditions.

8. Payment Method Analysis
Electronic-check customers had the highest observed churn rate.
Payment Method	Churn Rate
Electronic check	45.3%
Mailed check	19.1%
Bank transfer	16.7%
Credit card	15.2%
This relationship should be investigated further to determine whether payment experience, billing friction or differences in customer characteristics contribute to the observed pattern.

9. Customer Charges and Churn
Churned customers had an average monthly charge of approximately $74.44, compared with $61.27 among retained customers.
This suggests that higher monthly charges are associated with greater churn in this dataset. However, monthly charges may also be related to the services customers use, so further analysis is required before concluding that price itself is the underlying cause.

10. Key Business Insights
Insight 1: Early-stage customers are the highest-risk group
Customers in their first three months had a 56.2% churn rate. Churn decreased substantially as tenure increased.
Insight 2: Month-to-month customers require particular attention
The month-to-month segment had a 42.7% churn rate, considerably higher than customers on longer-term contracts.
Insight 3: Service type is associated with different churn levels
Fiber-optic customers had a 41.9% churn rate, suggesting that this segment should be investigated to understand the underlying drivers.
Insight 4: Payment method may provide a useful retention signal
Electronic-check customers had a 45.3% churn rate. The business should investigate whether billing or payment experience contributes to this pattern.
Insight 5: Retention improves significantly with customer tenure
The churn rate declined from 56.2% among customers with 0–3 months of tenure to 6.6% among customers with 61–72 months of tenure.

11. Recommendations
1. Strengthen early customer onboarding
Develop a structured customer onboarding programme covering the first 3–6 months. This could include service check-ins, technical support, product education and customer satisfaction monitoring.
2. Develop targeted strategies for month-to-month customers
Test incentives that encourage customers to move to longer-term contracts, while ensuring that offers are financially sustainable for the business.
3. Investigate the fiber-optic customer experience
Conduct deeper analysis of fiber customers to understand whether pricing, service quality, installation, technical support or competitor activity is contributing to the high observed churn.
4. Investigate electronic payment behaviour
Review billing and payment records to determine whether electronic-check customers experience different payment or billing issues.
5. Develop a churn-risk monitoring system
Use customer characteristics such as tenure, contract type, monthly charges, internet service and payment method to identify customers who may require proactive engagement.
6. Measure retention interventions
Retention initiatives should be evaluated using measurable outcomes such as churn reduction, retention rate, customer lifetime value and incremental revenue rather than assuming that every intervention will work equally well.

12. Dashboard Design
The Power BI dashboard was designed around five key areas:
1.	Overall churn KPIs
2.	Churn by customer tenure
3.	Churn by contract type
4.	Churn by internet service and payment method
5.	Customer segmentation and retention analysis
Interactive filters can be provided for contract type, internet service, payment method, senior-citizen status, partner status and dependents.

13. Limitations
The dataset does not contain explicit customer-reported churn reasons, signup dates or cancellation dates. Therefore, this analysis cannot identify the actual stated reasons why individual customers left or construct traditional signup-month cohorts.
Instead, tenure bands were used to represent different stages of the customer lifecycle, while customer characteristics were analysed as factors associated with observed churn.
The relationships identified in this analysis should not automatically be interpreted as causal relationships. Further analysis using customer complaints, support tickets, satisfaction surveys, cancellation reasons and transaction history would provide additional evidence.

14. Conclusion
The analysis shows that customer churn is concentrated among particular customer lifecycle stages and segments. Overall churn was 26.54%, with particularly high churn among customers with short tenure, month-to-month contracts, fiber-optic service and electronic-check payment methods.
The strongest retention opportunity identified by the analysis is the early customer lifecycle, where churn is substantially higher than among long-term customers. A combination of improved onboarding, targeted retention initiatives, service-quality investigation and data-driven churn monitoring could help the business better understand and manage customer retention.
The next analytical step would be to combine this dataset with customer feedback, support interactions and explicit churn reasons to distinguish correlation from potential causes and develop a more accurate customer-level churn prediction model.

