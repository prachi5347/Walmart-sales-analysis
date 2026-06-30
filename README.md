# 🛒 Walmart Sales Analysis using Python & SQL

 Overview

This project analyzes Walmart sales data using **Python**, **SQL (DuckDB)**, and **Google Colab**. The goal is to clean the dataset, perform SQL-based analysis, create visualizations, and generate business insights that can support data-driven decision-making.

This project demonstrates practical data analytics skills, including data cleaning, SQL querying, exploratory data analysis (EDA), and data visualization.



 Objectives

- Clean and preprocess Walmart sales data.
- Perform SQL analysis using DuckDB.
- Analyze sales performance across cities, branches, and product categories.
- Understand customer payment preferences.
- Visualize sales trends and business metrics.
- Generate actionable business insights.



Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- DuckDB (SQL)
- Google Colab


Dataset

The dataset contains Walmart retail transaction data with the following information:

- Invoice ID
- Branch
- City
- Category
- Unit Price
- Quantity
- Date
- Payment Method
- Rating
- Total Amount


Data Cleaning

The following preprocessing steps were performed:

- Removed missing values
- Converted the `date` column to DateTime format
- Converted `unit_price` to numeric values
- Created a new column:

python
Total Amount = Unit Price × Quantity


- Verified data types
- Checked for duplicate and null values



 SQL Analysis

The project answers several business questions using SQL queries:

- Total number of transactions
- Total sales revenue
- Top-performing cities by sales
- Sales by product category
- Branch-wise sales comparison
- Average customer rating by category
- Monthly sales trend
- Most preferred payment method


 Visualizations

The notebook includes visualizations such as:

- 📈 Top Cities by Sales
- 📊 Category-wise Sales
- 📅 Monthly Sales Trend
- 💳 Payment Method Distribution


 Key Insights

- Identified the cities generating the highest revenue.
- Compared sales performance across Walmart branches.
- Determined the highest-selling product categories.
- Analyzed customer payment preferences.
- Evaluated customer satisfaction using ratings.
- Observed monthly sales trends to identify business patterns.




Walmart-Sales-Analysis/
│
├── walmart.ipynb
├── Walmart.csv
├── README.md




Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Queries
- DuckDB
- Python Programming
- Data Visualization
- Business Analytics
- Google Colab

 Skills

- Python
- SQL
- Power BI
- Excel
- Data Visualization
- Business Analytics
