# Online-Retail-Sales-Analysis-Bestsellers-Customer-Buying-Patterns
Data Cleaning and Exploratory Data Analysis

# Project Overview
This project analyzes transactional data from an online retail business to identify bestselling products and peak customer purchasing times.
The goal is to demonstrate a real-world data analytics workflow, from data quality checks to actionable business insights.
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

# Analysis Performed Using Excel(pivotTables, Bar charts, and linegraphs).

# Top 10 Bestselling Products (by Quantity)
<img width="562" height="308" alt="image" src="https://github.com/user-attachments/assets/664d9daf-5a47-4154-b439-5e47349b0296" />

# Top 10 Revenue-Generating Products
<img width="512" height="303" alt="image" src="https://github.com/user-attachments/assets/bde46b75-c1d1-4566-bcca-ccfcc89b6706" />

# Total Sales by year, month
2011
<img width="151" height="25" alt="image" src="https://github.com/user-attachments/assets/b1825877-61e4-4588-95fa-30d44354aa9c" />
<img width="303" height="350" alt="image" src="https://github.com/user-attachments/assets/becf0a84-d66a-4eb9-afe5-58a107421c8c" />










