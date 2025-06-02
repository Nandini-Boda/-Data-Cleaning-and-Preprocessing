 Overview
This repository contains my submission for Task 1: Data Cleaning and Preprocessing as part of the Data Analyst Internship. The task was to clean a raw dataset by identifying and fixing issues such as missing values, duplicates, inconsistent formatting, and incorrect data types.

I chose the Netflix Movies and TV Shows dataset from Kaggle and completed the task using both Excel and Google Colab (Python) to showcase my ability to work across tools.

Tools & Technologies Used
Excel – For quick inspection, filtering, and initial cleanup

Google Colab – For deeper data cleaning using Python

Python Libraries: pandas, numpy

Dataset Source: Netflix Movies and TV Shows – Kaggle

In Excel:
Opened the original CSV file and checked for obvious issues

Removed duplicate rows using the "Remove Duplicates" feature

Renamed column headers to be cleaner (lowercase, no spaces)

Filled missing values in some cells with contextually appropriate placeholders (e.g., "Not Available")

In Google Colab (Python):
Loaded the cleaned Excel file using pandas.read_csv()

Double-checked for any remaining duplicates using .drop_duplicates()

Identified missing values using .isnull().sum()

Filled missing values in key columns like director, cast, and country

Standardized text columns (e.g., all lowercase for type, country)

Converted the date_added column to proper datetime format using pd.to_datetime()

Verified and corrected data types (e.g., release_year as int)

Exported the final cleaned dataset to a new .csv file

📂 Files Included
netflix_data_cleaning.ipynb – Google Colab notebook with full code and explanation

netflix_original.csv – Raw dataset as downloaded from Kaggle

netflix_cleaned.xlsx – Excel-cleaned version

netflix_cleaned.csv – Final cleaned version exported from Python



📌 Key Improvements Made
-Removed all duplicate entries

- Filled or flagged all missing values appropriately

- Standardized inconsistent text formats

- Converted date fields to consistent format (e.g., dd-mm-yyyy)

- Renamed columns to be clean and readable

- Ensured all data types were correct for future analysis

