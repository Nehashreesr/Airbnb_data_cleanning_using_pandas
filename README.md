Airbnb Data Cleaning Using Pandas
📌 Overview

This project focuses on cleaning and preparing Airbnb dataset(s) using Python and Pandas. 
The objective is to process raw Airbnb data, fix quality issues, handle missing values, standardize formats, and prepare the dataset for further analysis, visualization, or dashboard creation.
Dataset

Source: Airbnb dataset (CSV format)

Contents: Includes details such as listing information, host details, pricing, availability, reviews, etc. (Modify based on your dataset)

Goal: Convert raw, inconsistent Airbnb data into a clean, structured format suitable for analytics.
🚀 Steps Performed
1️⃣ Import & Load Dataset

Loaded the raw Airbnb CSV file using Pandas

Inspected dataset structure:

.head()

.shape()

.info()

.describe()

2️⃣ Exploratory Data Checks

Performed initial checks to understand data quality issues:

Identified missing values

Checked for duplicates

Inspected inconsistent formats (dates, prices, categories)

Reviewed column types

3️⃣ Data Cleaning Using Pandas

All cleaning operations were done using Pandas, including:

✔ Handling Missing Values

Dropped columns with excessive missing data

Filled missing values using mean/median/mode (as appropriate)

Replaced blank or null strings

✔ Removing Duplicate Records

Used drop_duplicates() to eliminate repeated entries

✔ Fixing Data Types

Converted price-related columns to numeric

Converted date columns to datetime

Cleaned categorical values

✔ Standardizing Data

Renamed inconsistent column names

Removed special characters from price fields

Normalized string cases (title case / lower case)

✔ Outlier Treatment (If applicable)
✔ Exporting Cleaned Data

Saved cleaned dataset as:

cleaned_airbnb_data.csv

Detected outliers using IQR or Z-score

Removed or capped extreme values (e.g., unrealistic prices, reviews)
