# Task 1 - Data Cleaning and Preprocessing

**Dataset:** Mall Customers  
**Tool Used:** Google Colab (Python, Pandas)

## Overview
This project cleans the Mall Customers dataset by handling missing values, removing duplicates, fixing formats, and checking outliers.

## Steps Performed
- Loaded dataset using pandas.
- Renamed columns (lowercase, no spaces).
- Filled missing values with median.
- Standardized gender values (male/female).
- Removed duplicates.
- Capped income outliers using IQR.
- Saved cleaned file as `mall_customers_cleaned.csv`.

## Files in this Repository
- `mall_customers.csv` — original dataset  
- `mall_customers_cleaned.csv` — cleaned dataset  
- `data_cleaning_mall.ipynb` — Google Colab notebook  

## Results
- No missing or duplicate rows.
- Gender standardized.
- Outliers capped.

## Author
Bhuvana Kata
