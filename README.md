# Customer-Churn-Analysis--PowerBI
Dataset: Size: 10,000 records, Primary Key: Customer ID
Features:
1.	Credit Score: Numeric value representing the credit score of the customer.
2.	Country: Country of the customer.
3.	Age: Age of the customer.
4.	Gender: Gender of the customer.
5.	Tenure: Number of years the customer has been with the bank.
6.	Balance: Account balance of the customer.
7.	Product Number: Number of products the customer has with the bank.
8.	Active Member: Indicates whether the customer is an active member (binary: 1 for active, 0 for inactive).
9.	Estimated Salary: Estimated salary of the customer.
10.	Churn Status: Indicates whether the customer has churned (binary: 1 for churned, 0 for active).
Transformations:
1.	Data Type Conversions: Converted appropriate columns to their respective data types.
2.	Creation of Ranges: Age, credit score, and balance were categorized into ranges.
3.	Text Data Transformation: Transformed churn status, active member, and product number into text data types.
4.	New Tables Creation: Created tables based on age range, credit score range, and balance range.
5.	Modeling: Modeled new tables with the original dataset for enhanced analysis.

Introduction: This report provides an analysis of customer churn for a bank based on the provided dataset. The data consists of information on 10,000 customers, including their demographics, financial details, and churn status. The aim is to understand churn patterns and identify factors influencing customer attrition.
Key Findings:
1.	Overall Churn Rate:
•	The overall churn rate across the bank 20.4% is above the targeted range of 12%.
•	Detailed analysis reveals variations in churn rates across different customer parameters.
2.	Demographic Insights:
•	Age: Customers aged between 51-60 exhibit the highest churn rate. Younger and older demographics show comparatively lower churn rates.
•	Gender: Churn rate among male customers is slightly higher than among female customers.
•	Country: Churn rates vary across France is more than half compared to Germany and Spain.
3.	Financial Insights:
•	Credit Score: Customers with lower credit scores tend to have higher churn rates.
•	Balance: Churn rate is relatively lower among customers with higher account balances.
•	Product Usage: Customers with product 1 and product 2 are more likely to churn.
•	Credit Card: Customers owning a credit card has higher churn rate than those who do not own.


![image](https://github.com/Vd1299/Customer-Churn-Analysis--PowerBI/assets/60086631/cf76891c-db8c-484a-a47b-e1a3b3428839)
