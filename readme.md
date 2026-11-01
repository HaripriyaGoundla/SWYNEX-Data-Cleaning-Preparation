
# SWYNEX Data Cleaning & Preparation

## Project Overview
This project focuses on cleaning and preparing a raw customer dataset for analysis as part of Task 1 of the SWYNEX internship.

## Dataset
- Dataset: Sample Customer Dataset
- Format: CSV
- Original records: 15

## Tools Used
- Python
- Pandas
- NumPy
- Google Colab

## Data Quality Issues Identified
1. Missing values
2. Duplicate customer records
3. Incorrect data types
4. Inconsistent names and email formatting
5. Inconsistent country names
6. Inconsistent date and amount formats
7. Invalid customer records
8. Negative amount requiring review

## Cleaning Process
- Standardized column names and text values
- Removed unnecessary spaces
- Converted emails to lowercase
- Standardized country names
- Converted signup dates to datetime
- Converted amounts to numeric values
- Standardized active status to Boolean
- Removed duplicate customer records
- Removed one invalid customer record
- Flagged negative amounts for review
- Exported the cleaned dataset to CSV

## Results
- Original records: 15
- Duplicate customer records removed: 4
- Invalid records removed: 1
- Final records: 10

## Conclusion
This project demonstrates a basic data-cleaning workflow using Python and Pandas. The cleaned dataset is more consistent and ready for further analysis.
