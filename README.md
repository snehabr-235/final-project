# E-commerce Orders Dataset – Data Cleaning & Preprocessing

## 📌 Project Overview
This project focuses on cleaning and preprocessing a messy E-commerce Orders dataset using **Python in Google Colab**.

The main objective is to improve data quality by handling missing values, correcting data types, removing duplicate records, standardizing data, and preparing the dataset for further analysis and visualization.

## 📂 Dataset Information
- **Dataset Name:** E-commerce Orders
- **Original File:** `ecommerce_orders_messy.csv`
- **Cleaned File:** `ecommerce_orders_cleaned.csv`
- **Rows:** 5,197
- **Columns:** 28
- **Tool Used:** Google Colab
- **Programming Language:** Python

## 🛠️ Tools and Libraries
- Python
- Google Colab
- Pandas
- NumPy

## 🧹 Data Cleaning and Preprocessing Steps

The following preprocessing operations were performed:

1. **Data Loading:** Imported the original CSV dataset using Pandas.
2. **Missing Value Handling:** Identified missing values and applied appropriate filling techniques.
3. **Duplicate Removal:** Checked and removed duplicate records.
4. **Data Type Conversion:** Converted numerical columns into appropriate numeric formats.
5. **Date Conversion:** Converted the `order_date` column into datetime format.
6. **Median Imputation:** Filled missing `delivery_days` values using the median.
7. **Text Cleaning:** Standardized text values and handled inconsistent formatting.
8. **Feature Engineering:** Extracted `order_month` and `order_year` from the order date.
9. **Calculated Columns:** Created additional columns such as `total_product_value`, `discount_amount`, and `final_calculated_amount`.
10. **Final Dataset Export:** Exported the processed dataset into CSV format.

## 📊 Final Dataset Columns

The cleaned dataset contains 28 columns, including:

- Order Information
- Customer Information
- Product and Category
- Quantity and Unit Price
- Discount and Shipping Fee
- Payment Method and Order Status
- Customer Age and Rating
- Delivery Days
- Calculated Financial Columns
- Order Month and Order Year

## 🎯 Project Outcome

The project demonstrates practical data preprocessing skills using Python and Pandas. The processed dataset is structured for further exploratory data analysis (EDA), business intelligence reporting, and dashboard development using Power BI.

## 🚀 Future Scope

- Exploratory Data Analysis (EDA)
- Sales and Revenue Analysis
- Customer Behaviour Analysis
- Product Performance Analysis
- Interactive Power BI Dashboard

## 👩‍💻 Conclusion

This project provided hands-on experience in handling real-world messy data and applying essential data-cleaning techniques. It helped improve understanding of data quality, missing value treatment, data type conversion, and feature engineering.
