# cleaned-data-project
📊 Flipkart Product Data Analysis
📌 Project Overview

This project analyzes a Flipkart product dataset to understand pricing patterns, discounts, product categories, and outliers.
The main goal is to clean, transform, and visualize the data to generate insights that can help in product performance analysis.

📂 Dataset Details

Source: Flipkart scraped product dataset

Main Columns:

product_name – Name of the product

product_category_tree – Product category hierarchy

retail_price – Original price before discount

discounted_price – Price after discount

discount_percentage – Calculated discount percentage

overall_rating – Customer rating of the product

🛠 Steps Performed
1. Data Cleaning

Removed duplicates

Handled missing values (replaced with 0 or NaN where appropriate)

Corrected data types

2. Feature Engineering

Created discount_percentage =
(retail_price−discounted_price)/retail_price×100

3. Data Transformation

Filtering products with discount > 50%

Grouping by category and finding max/min prices

4. Outlier Detection

Used boxplots to visualize outliers in numeric columns

📊 Key Insights

Many products have discounts above 50%

Certain categories consistently have higher retail prices

Outliers mostly appear in retail_price and discounted_price columns
