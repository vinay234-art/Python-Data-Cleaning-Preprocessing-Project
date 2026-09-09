# Python Data Cleaning & Preprocessing Project

## Project Overview

This project demonstrates a practical **Data Cleaning and Data Preprocessing workflow using Python and Pandas**. The objective of the project is to inspect a raw Excel dataset, identify data quality issues, clean and transform the data, and prepare a structured dataset that can be used for further data analysis.

The project starts by importing the dataset from an Excel file and performing an initial inspection of the data using Pandas. Various checks are performed to understand the dataset structure, data types, missing values, duplicate records, and statistical information.

## Key Tasks Performed

* Imported the Excel dataset using **Pandas**
* Performed initial data inspection using:

  * `head()`
  * `shape`
  * `describe()`
  * `columns`
  * `info()`
  * `dtypes`
* Checked for missing/null values
* Identified missing values in the `CouponCode` column
* Replaced missing coupon values with **"No Coupon"**
* Checked and removed duplicate records
* Checked duplicate `OrderID` values
* Converted the `Date` column into a proper datetime format
* Created new date-related columns:

  * `Year`
  * `Month`
  * `Day`
* Checked negative and zero values in:

  * `Quantity`
  * `UnitPrice`
  * `TotalPrice`
* Cleaned text columns using string stripping
* Checked unique values in important categorical columns
* Performed final data-quality checks
* Exported the cleaned dataset into a new Excel file named `Cleaned_Dataset_DA.xlsx`

## Dataset

The dataset contains **1,200 records** and includes fields related to orders, customers, products, pricing, shipping, payment methods, order status, coupons, referrals, and cart information. The project uses the Excel dataset as the source for the cleaning and preprocessing workflow.

## Tools & Technologies

* **Python**
* **Pandas**
* **Jupyter Notebook**
* **Microsoft Excel**

## Project Objective

The main objective of this project is to demonstrate how Python can be used to transform raw business data into a cleaner and more structured format. Data cleaning is an important step in the data analysis process because accurate and consistent data helps produce more reliable analysis and business insights.

## Output

After completing the cleaning and preprocessing steps, the cleaned dataset is exported to an Excel file:

`Cleaned_Dataset_DA.xlsx`

This cleaned dataset can be used for further **Exploratory Data Analysis (EDA), visualization, reporting, and business analysis**.

## Skills Demonstrated

* Data Loading
* Data Inspection
* Data Cleaning
* Missing Value Handling
* Duplicate Detection & Removal
* Data Type Conversion
* Date & Time Processing
* Data Validation
* String Cleaning
* Data Preprocessing
* Excel File Handling using Python

## Conclusion

This project provides hands-on experience with a real-world style data-cleaning workflow using Python and Pandas. It demonstrates the process of taking a raw Excel dataset, identifying common data-quality issues, cleaning and transforming the data, and preparing it for further analysis.

