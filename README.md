# Swiggy Data Cleaning with MySQL

This project involves cleaning a Swiggy dataset sourced from Kaggle using MySQL. The raw data (`swiggy_50`) was processed and transformed into a cleaned, final dataset (`swiggy.sql_FINAL`), ensuring high-quality, structured data ready for further analysis.

## Project Overview

- **Dataset**: Swiggy data sourced from Kaggle
- **Raw Data**: `swiggy_50`
- **Cleaned Data**: `swiggy.sql_FINAL`
- **Tools Used**: MySQL for data cleaning and transformation

## Key Cleaning Steps

1. **Handling Missing Values**: 
   - Removed records with incomplete or missing information.
   - Imputed missing values where possible.
   
2. **Duplicate Removal**: 
   - Identified and removed duplicate records.

3. **Standardizing Data Types**: 
   - Ensured consistency in data types across columns (e.g., date formats, string trimming).

4. **Normalization**: 
   - Reformatted and standardized entries such as addresses, restaurant names, and category labels.

5. **Outlier Detection and Removal**: 
   - Removed or flagged potential outliers to ensure more robust analysis.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/swiggy-data-cleaning.git
