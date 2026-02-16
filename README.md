# Customer-Behavior-Analysis

Customer Shopping Behavior Analysis using Python, SQL, and Power BI. Includes data cleaning, feature engineering, PostgreSQL integration, business queries, and an interactive dashboard. Analyzes 3,900 transactions to uncover insights on revenue, customer segments, product trends, discounts, and subscriptions

📊 Customer Shopping Behavior Analysis

A complete end-to-end analytics project examining 3,900 customer transactions to uncover insights about spending patterns, product preferences, discount behavior, and subscription trends.
This project includes Python-based EDA, PostgreSQL business analysis, and a Power BI dashboard for final visualization.

📁 Table of Contents

Project Overview
Dataset Summary
Tech Stack
Features
Project Workflow
Exploratory Data Analysis (Python)
SQL Business Analysis
Power BI Dashboard
Key Insights
Business Recommendations
How to Run the Project
Folder Structure

🚀 Project Overview

This project analyzes customer shopping behavior using transactional and demographic data. The aim is to help businesses understand spending trends, identify customer groups, optimize discount strategies, and improve product positioning.

📊 Dataset Summary

Rows: 3,900
Columns: 18
Includes:
Customer demographics (age, gender, subscription status, location)
Purchase details (product, category, season, color, size, amount)
Behavior metrics (discount usage, shipping type, rating, frequency of purchases)
Missing Values: 37 missing ratings (handled with median imputation)

🛠️ Tech Stack

ComponentTechnology UsedProgrammingPythonDatabasePostgreSQLVisualizationPower BILibrariesPandas, NumPy, Matplotlib, SQLAlchemy⭐ Features
Clean and preprocess raw data
Handle missing values using category-wise median imputation
Generate new features (age groups, purchase frequency)
Load cleaned data into PostgreSQL
Run business-focused SQL queries
Build interactive Power BI dashboard

🔄 Project Workflow

Data Cleaning & Preparation (Python)
Feature Engineering
Database Integration (PostgreSQL)
Business Analysis (SQL)
Dashboard Creation (Power BI)
Insights & Recommendations

🐍 Exploratory Data Analysis (Python)

Key steps performed:
Inspected dataset structure using info(), describe()
Filled missing review_rating values using median per category
Standardized column names to snake_case
Created new engineered fields:
age_group
purchase_frequency_days
Removed redundant promo_code_used column
Loaded data into PostgreSQL using SQLAlchemy

🧮 SQL Business Analysis

Business questions answered using SQL:
Revenue by Gender
High-Spending Discount Users
Top 5 Products by Rating
Standard vs Express Shipping Comparison
Subscriber vs Non-Subscriber Performance
Top Discount-Dependent Products
Customer Segmentation: New / Returning / Loyal
Top 3 Products per Category
Repeat Buyers vs Subscription Correlation
Revenue by Age Group

📈 Power BI Dashboard

The final interactive dashboard visualizes:
Revenue trends
Product performance
Customer segmentation
Subscription analysis
Age group spending
Shipping type comparison

🔑 Key Insights

Some age groups contribute disproportionately to total revenue.
Express shipping users tend to spend more.
Discount use does not always imply lower spend — some high spenders use discounts frequently.
Subscribers generate more revenue on average.

💡 Business Recommendations

Promote subscription benefits to increase long-term revenue
Launch loyalty programs to boost repeat purchases
Optimize discount strategy to protect margins
Highlight top-rated products in marketing campaigns
Target high-spending age groups with personalized promotions

