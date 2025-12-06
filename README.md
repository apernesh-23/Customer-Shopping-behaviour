🛒 Customer Shopping Behavior Analysis
📊 Python • 🗄 SQL (PostgreSQL) • 📈 Power BI




🌟 Project Summary

This project performs an end-to-end analysis of 3,900 customer purchase records to deeply understand who buys, what they buy, and how their shopping behavior changes across demographics and categories.

It combines:

Python for EDA

PostgreSQL for business SQL analysis

Power BI for storytelling dashboards

The goal is to help businesses improve revenue, target customers better, optimize discounts, and boost subscriptions.

📂 Dataset Overview
Feature Type	Details
Rows	3,900
Columns	18
Includes	Age, Gender, Location, Purchase Amount, Category, Season, Size, Color, Subscription, Review Rating, Previous Purchases, Discount, Shipping Type
Missing Data	37 null values in Review Rating

Key Insight:
Data cleaning & imputation steps were applied to handle missing ratings using category-wise median values.

🧹 Data Cleaning & EDA (Python)

✔ Loaded dataset using Pandas
✔ Performed .info(), .describe() & statistical exploration
✔ Handled missing values (median imputation)
✔ Converted columns to snake_case
✔ Engineered new features like:

age_group

purchase_frequency_days
✔ Dropped redundant promo_code_used feature
✔ Connected Python to PostgreSQL and loaded clean data using psycopg2

📌 Notebook & scripts are inside the notebooks / scripts folder.

🧠 Business Insights via SQL (PostgreSQL)

A rich set of SQL analyses were performed, including:

🔹 Revenue Insights

Revenue split by gender

Revenue contribution by age group

Spending power comparison: Subscribers vs. Non-subscribers

🔹 Product Preference Insights

Top 5 highest-rated products

Top 3 most purchased products per category

🔹 Customer Behavior

High-spending discount users

Discount-dependent items

Customer segmentation: New, Returning, Loyal

Repeat buyers and subscription correlation

🔹 Shipping Analysis

Standard vs Express shipping spend difference

📁 All SQL scripts are included in /sql_queries/.

📊 Power BI Dashboard

The interactive dashboard includes:

⭐ Total Revenue Overview

🧑‍🤝‍🧑 Customer Demographics

🛍 Category & Product Insights

🔄 Subscription vs Revenue Story

🚚 Shipping Preferences

❤️ Top Rated Products

🎯 Customer Segments

Perfect for business decision-making and presentations.

🚀 Tech Stack
Component	Technology
Language	Python
Database	PostgreSQL
Libraries	Pandas, NumPy, Matplotlib, Seaborn
Dashboard	Power BI
Version Control	Git, GitHub

💡 Business Recommendations

🎯 Boost Subscriptions
Offer personalized benefits to convert more customers.

🤝 Strengthen Loyalty Programs
Reward frequent buyers to push them into “Loyal” category.

💸 Optimize Discount Strategy
Identify products overly dependent on discounts.

⭐ Highlight Top Rated Products
Use them in marketing campaigns.

🚚 Promote Express Shipping
Higher-revenue customers prefer faster delivery.

🎯 Target High-Value Age Groups
Focus marketing on the top-performing demographics.

🎉 Conclusion

This project brings together Python, SQL, and Power BI to create a powerful, end-to-end customer behavior analysis system.
It showcases strong skills in:

✔ Data Cleaning
✔ Data Engineering
✔ SQL Business Analytics
✔ Dashboard Visualization
✔ Insight Generation
