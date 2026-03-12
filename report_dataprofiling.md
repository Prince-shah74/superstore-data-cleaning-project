# Data Profiling Report

## Missing Values
Postal Code: 11 missing values

## Duplicate Records
0 duplicate rows found

## Data Types
Order Date: object
Sales: float

## Potential Issues
Order Date and Ship Date need conversion to datetime.
Postal Code has missing values.

# Superstore Data Cleaning and Preparation

## Project Overview
This project focuses on the first critical step in data analysis: acquiring, profiling, cleaning, and preparing raw data for analysis.

## Dataset
The dataset used is the Superstore Sales Dataset containing information about customer orders, products, and sales.

## Data Profiling
Initial data profiling identified the following issues:
- Missing values in Postal Code column
- Inconsistent date formats
- Unrealistic shipping duration values

## Data Cleaning Steps
1. Handled missing values in Postal Code using median.
2. Converted Order Date and Ship Date into datetime format.
3. Checked and confirmed no duplicate rows.
4. Created new features:
   - Order Year
   - Order Month
   - Shipping Days
5. Removed unrealistic shipping durations.

## Final Output
A cleaned and analysis-ready dataset saved as `cleaned_dataset.csv`.

## Tools Used
- Python
- Pandas
- Data Profiling
- Feature Engineering