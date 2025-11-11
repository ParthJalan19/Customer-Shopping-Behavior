Customer Shopping Behavior Analysis
Overview

This project analyzes customer shopping behavior to uncover patterns in purchasing, spending, and loyalty. Using Python, SQL Server, and Power BI, it transforms raw transactional data into meaningful insights to help businesses improve engagement, marketing effectiveness, and revenue.

Objectives

Understand customer purchase trends by age, gender, and category.

Analyze how discounts, reviews, and subscriptions influence spending.

Identify loyal and high-value customer segments.

Provide actionable business recommendations through visualization.

Workflow
1. Data Preparation (Python)

Imported and explored data using Pandas.

Cleaned missing values (review_rating filled with category median).

Standardized column names (snake_case).

Created new features:

age_group based on customer age.

purchase_frequency_days derived from frequency labels.

Removed redundant columns (promo_code_used).

2. SQL Analysis (SQL Server)

Imported the cleaned dataset into SQL Server.

Wrote queries to generate key insights:

Revenue by gender and age group.

Top-rated and most-purchased products.

Customer segmentation: New, Returning, Loyal.

Effect of discounts and shipping type on spending.

3. Data Visualization (Power BI)

Built an interactive dashboard displaying:

Revenue by age group and gender.

Product performance by category.

Customer segment distribution.

Seasonal and discount-based sales analysis.

Comparison of standard vs. express shipping spend.

Key Insights

Adult and Middle-Aged customers generate the most revenue.

Express shipping users spend significantly more.

Loyal customers contribute high revenue despite smaller numbers.

Apparel products dominate both purchases and discount usage.

Highly rated products correlate with repeat purchases.

Business Recommendations

Launch targeted loyalty programs to retain frequent buyers.

Optimize discount strategies for profitability.

Highlight top-rated products in marketing campaigns.

Promote subscriptions and express shipping options.

Focus marketing on high-value demographic segments.

Tools and Technologies

Python (Pandas, NumPy) – Data cleaning and transformation

SQL Server (SSMS) – Querying and structured analysis

SQLAlchemy – Python-SQL connection

Power BI – Dashboard creation and visualization

Project Files
File	Description
customer_shopping_behavior.csv	Original dataset
cleaned_customer_shopping_behavior.csv	Processed dataset
Customer_shopping_behavior.pbix	Power BI dashboard
Business Problem Document.pdf	Problem statement and deliverables
Customer Shopping Behavior Analysis.pdf	Final analytical report
analysis_notebook.ipynb	Python data preparation notebook
sql_queries.sql	SQL analysis scripts
Author

Jalan Parth Santosh
Developer and data enthusiast passionate about analytics, backend systems, and intelligent data solutions.
