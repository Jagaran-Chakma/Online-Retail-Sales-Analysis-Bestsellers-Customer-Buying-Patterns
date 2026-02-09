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

# Analysis Performed
# Top 10 Bestselling Products (by Quantity)
<img width="562" height="308" alt="image" src="https://github.com/user-attachments/assets/664d9daf-5a47-4154-b439-5e47349b0296" />

	

# Top 10 Revenue-Generating Products
# Sales by Hour of Day
# Sales by Day of Week
Using pivotTables, Bar charts, and linegraphs.


# Results
	
Row Labels	Sum of UnitPrice
BREAD BIN DINER STYLE IVORY	4526.48
SPOTTY BUNTING	4536.89
IVORY KITCHEN SCALES	4547.2
DOORMAT KEEP CALM AND COME IN	4931.86
SET OF 3 CAKE TINS PANTRY DESIGN 	5064.39
VINTAGE RED KITCHEN CABINET	5075
CREAM SWEETHEART MINI CHEST	5438.11
WHITE HANGING HEART T-LIGHT HOLDER	5615.22
PARTY BUNTING	6379.37
REGENCY CAKESTAND 3 TIER	17849.95
Grand Total	63964.47
	
![Uploading image.png…]()









