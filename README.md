Customer Churn Analysis
Overview

This project presents an exploratory data analysis (EDA) of a customer churn dataset to identify key factors influencing customer attrition. The objective is to uncover actionable insights that can help improve customer retention and support data-driven business decisions.

Objectives
Analyze customer behavior and service usage patterns
Identify key drivers contributing to churn
Segment high-risk customers
Provide strategic recommendations to reduce churn
Dataset Information
Total Records: 7,043 customers
Features: 21 variables
Data includes:
Customer demographics (gender, senior citizen, partner, dependents)
Account information (tenure, contract type, payment method)
Services subscribed (internet, security, support, streaming)
Billing details (monthly charges, total charges)
Target variable: Churn
Tools and Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Key Insights
1. Overall Churn Rate
Churn Rate: 26.5%
Approximately one in four customers has discontinued services
2. Contract Type Impact
Month-to-month: ~43% churn
One-year: ~11% churn
Two-year: ~3% churn

Customers with shorter contracts show significantly higher churn.

3. Tenure Analysis
Customers with tenure < 12 months have the highest churn
Long-tenure customers (>24 months) are more likely to stay

Early-stage customers are more prone to churn.

4. Service Influence
Fiber optic users: ~41% churn
DSL users: ~19% churn

Higher churn among fiber users may indicate pricing or service quality concerns.

5. Value-Added Services
Without Tech Support / Online Security: 30–40% churn
With these services: <20% churn

Additional services improve customer retention.

6. Payment Method
Electronic check: ~45% churn
Automatic payments: ~15–18% churn

Customers using auto-payment methods show better retention.

7. Pricing Impact
Higher monthly charges correlate with higher churn

Price sensitivity plays a significant role in customer attrition.

High-Risk Customer Segment

Customers most likely to churn typically have:

Month-to-month contracts
Low tenure (<12 months)
Fiber optic service
No value-added services
Electronic check payment method
Higher monthly charges
Business Recommendations
Promote long-term contracts through incentives
Strengthen onboarding and engagement for new customers
Bundle value-added services to increase retention
Encourage adoption of automatic payment methods
Offer targeted pricing or loyalty benefits for high-paying customers
Conclusion

Churn is driven by identifiable behavioral and service-related factors. By focusing on contract structure, early customer engagement, service adoption, and payment behavior, businesses can significantly reduce churn and improve customer lifetime value.
