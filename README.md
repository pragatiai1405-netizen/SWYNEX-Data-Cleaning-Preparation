# SWYNEX Task 1 – Data Cleaning & Preparation

## Project Overview

This project was completed as part of the SWYNEX Technologies Data Analyst Internship.

The objective of this task was to clean and prepare a public dataset using Python and Pandas.

## Dataset

**Dataset:** Online Retail II  
**Data Used:** Year 2009–2010

The dataset contains online retail transaction information such as invoice numbers, stock codes, product descriptions, quantities, invoice dates, prices, customer IDs, and countries.

## Tools Used

- Python
- Pandas
- Google Colab

## Data Cleaning Performed

The following data cleaning steps were performed:

1. Identified missing values.
2. Removed **6,865 duplicate records**.
3. Removed **2,928 records with missing product descriptions**.
4. Filled missing Customer ID values with `0` to represent unknown customers.
5. Converted the Customer ID column from `float64` to `int64`.
6. Removed extra whitespace from Country values.
7. Verified that the final dataset contains **0 missing values**.

## Final Dataset

- **Rows:** 515,668
- **Columns:** 8
- **Missing Values:** 0
- **Duplicate Records Removed:** 6,865

## Output

The cleaned dataset is provided as:

`cleaned_online_retail_2009_2010.zip`

## Conclusion

The dataset was successfully cleaned and prepared for further data analysis. The cleaned data has consistent data types, no missing values, and duplicate records removed.
