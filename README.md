# Customer_behaviour_analysis
E-commerce customer analytics using SQL for sales, segmentation, and purchase behavior analysis, using Python, SQL, and Power BI

Overview

This project presents an end-to-end data analytics workflow focused on analyzing customer purchase behavior and extracting actionable business insights. The analysis covers the complete data pipeline, from dataset loading and preprocessing to exploratory analysis, SQL-based querying, and interactive dashboard visualization.

The primary objective of this project is to uncover patterns in customer transactions, purchasing behavior, discount utilization, and revenue contribution to support data-driven business decision-making.

This project demonstrates practical skills in:

Data loading and preprocessing
Exploratory Data Analysis (EDA)
Data cleaning and transformation
SQL querying using PostgreSQL
Business intelligence dashboard creation using Power BI
Insight generation and reporting
Dataset

The dataset contains customer transaction and purchase-related information, including attributes such as:

Customer ID
Gender
Age Group
Purchase Amount
Product Category
Item Purchased
Review Rating
Shipping Type
Discount Applied
Subscription Status
Previous Purchases

The dataset was used to analyze customer behavior patterns, purchasing trends, and overall business performance.

Tools & Technologies:-

Programming & Querying
Python
PostgreSQL
SQL

Python Libraries
Pandas

Data Visualization
Power BI

Development Environment
Jupyter Notebook
pgAdmin / PostgreSQL
Project Workflow

1. Data Loading

The dataset was imported into Python using Pandas for initial inspection and processing.

Tasks performed:

Loading CSV data
Checking structure and schema
Understanding variable distributions
2. Data Cleaning

Data preprocessing was performed to ensure consistency and accuracy.

Cleaning steps included:

Handling missing values
Removing duplicates
Standardizing data formats
Correcting inconsistent entries
Preparing data for SQL import
3. Exploratory Data Analysis (EDA)

EDA was performed to identify trends, anomalies, and relationships within the dataset.

Analysis included:

Revenue distribution analysis
Customer demographic insights
Product performance analysis
Discount usage trends
Shipping behavior analysis
Purchase frequency patterns

Visualizations were created to support data interpretation.

4. SQL Analysis (PostgreSQL)

The cleaned dataset was imported into PostgreSQL for advanced querying and business analysis.

Key SQL operations included:

Aggregate functions
Grouping and filtering
Subqueries
Common Table Expressions (CTEs)
Window functions
Ranking analysis
Customer segmentation

Business questions answered:

Revenue comparison by gender
Discount effectiveness analysis
Top-rated products
Shipping type performance
Subscriber vs non-subscriber spending behavior
Product discount trends
Customer segmentation analysis
Revenue contribution by age group

5. Dashboard Development

An interactive dashboard was created in Power BI to present analytical findings visually.

Dashboard components include:

Revenue KPIs
Customer segmentation charts
Product performance metrics
Discount analysis visuals
Purchase trend analysis
Regional/customer demographic insights

The dashboard enables quick exploration of key business metrics and supports strategic decision-making.

Dashboard Features

The Power BI dashboard provides:

Sales Performance Monitoring

Tracks overall revenue trends and purchasing behavior.

Customer Segmentation

Classifies customers based on purchase history.

Product Insights

Highlights top-performing products and categories.

Discount Analysis

Evaluates the impact of discount strategies.

Subscription Behavior

Compares spending patterns between subscriber and non-subscriber customers.

Demographic Analysis

Visualizes customer contributions by age group and gender.

Key Results

The analysis revealed several actionable insights:

Revenue distribution varies across customer demographics
Certain products consistently receive higher ratings
Discounted purchases significantly influence buying behavior
Repeat buyers show stronger subscription tendencies
Shipping preferences impact average purchase value
Specific customer segments contribute disproportionately to total revenue

These findings can help optimize:

Marketing strategies
Customer retention efforts
Pricing decisions
Product targeting
Subscription campaigns
