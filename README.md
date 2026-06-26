# MySQL-Company-Layoffs-Data-Cleaning
Data cleaning and transformation of company layoffs dataset using MySQL Workbench.

## Project Overview
This project focuses on cleaning and preparing a raw dataset regarding global company layoffs for subsequent analysis.

## Data Cleaning Steps Followed:
1. **Remove Duplicates:** Identified and removed duplicate rows using `ROW_NUMBER()`.
2. **Standardize Data:** Fixed spelling inconsistencies, updated text formatting, and standardized null values.
3. **Null Values:** Addressed blank or null fields (e.g., populating missing industry data where possible).
4. **Remove Unnecessary Columns/Rows:** Dropped columns and rows that weren't useful for the final analysis.

## How to Use
1. Download the `company_layoffs_data_cleaning.sql` file.
2. Import the raw dataset into MySQL Workbench.
3. Run the script to view the cleaned structure.
