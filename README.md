# Online-Retail-Sales-Analysis-Bestsellers-Customer-Buying-Patterns
Data Cleaning and Exploratory Data Analysis

# Project Overview
This project analyzes transactional data from an online retail business to identify bestselling products and peak customer purchasing times.
The goal is to demonstrate a real-world data analytics workflow — from data quality checks to actionable business insights.
Dataset source: https://www.kaggle.com/datasets/vijayuv/onlineretail
Dataset Size: 500,000+ transactions
Scope used: United Kingdom transactions (~35K rows)

# Data Quality Assessment
Before analysis, the dataset was reviewed for common real-world data issues:
Negative quantities indicate returns or cancellations.
Missing CustomerID values (guest checkouts).
Validation of date, numeric, and text data types.

# Data Cleaning & Preparation
Filtered dataset to United Kingdom customers only
Removed cancelled orders (InvoiceNo starting with ‘C’)
Created a calculated field:
TotalSales = Quantity × UnitPrice

# Analysis Performed
# Top 10 Bestselling Products (by Quantity)
# Top 10 Revenue-Generating Products
# Sales by Hour of Day
# Sales by Day of Week
Using pivotTables, Bar charts, and linegraphs.


# Results









