# Retail Sales Exploratory Data Analysis (Python)

## Project Overview
This project performs data cleaning, feature engineering, and Exploratory Data Analysis (EDA) on a retail sales dataset (`Pg_data.csv`) using Python in JupyterLab.

## Key Steps Performed
- **Data Cleaning & Validation:** Checked for missing values (`isnull().sum()`) and verified data types across 100 transactions and 24 columns.
- **Feature Engineering:** Created calculated business metrics including `gross_sales`, `discount_amount`, `net_sales`, `total_cost`, `profit`, and `profit_margin`.
- **Time-Series Extraction:** Converted `Order_Date` to datetime format to extract `day`, `month`, and `year` for monthly profitability trends.
- **Data Visualization:** Built distribution and category comparison charts using `Matplotlib` and `Seaborn`.

## Python Libraries Used
- **Pandas & NumPy** (Data Manipulation & Calculations)
- **Matplotlib & Seaborn** (Statistical Data Visualization)
