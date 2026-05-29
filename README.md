# Project Overview

This project focuses on cleaning and preprocessing a messy café sales dataset using Python and Pandas in Google Colab.
##  The dataset contains
- missing values
-  invalid entries (ERROR, UNKNOWN)
-  incorrect data types
-  duplicate records.

The goal of this project is to transform the raw dataset into a clean and analysis-ready format.
##  Tools Used

## Programming Language

* Python

## Libraries

* Pandas → Data manipulation and cleaning
* NumPy → Handling missing and invalid values

## Platform

* [Google Colab](https://colab.research.google.com?utm_source=chatgpt.com)

## File Format

* CSV (Comma Separated Values)

## Additional Tools

* Microsoft Excel (for viewing dataset)
* GitHub (for project hosting and version control)
# Data Cleaning Steps Performed

## 1. Loaded Dataset

Imported the CSV file using Pandas.

## 2. Replaced Invalid Values

Converted:

ERROR
UNKNOWN

into NaN values.

## 3. Cleaned Numeric Columns

Converted:

Quantity
Price Per Unit
Total Spent

to numeric data types.

## 4. Filled Missing Values
Used median values for numeric columns
Used mode values for categorical columns
## 5. Recalculated Total Spent

Calculated:
Total Spent = Quantity × Price Per Unit

for missing rows.

## 6. Fixed Date Column

Converted transaction dates into proper datetime format.

## 7. Removed Duplicate Rows

Deleted duplicate entries from the dataset.

## 8. Saved Cleaned Dataset

Exported cleaned data into:
cleaned_cafe_sales.csv
# Output

## The final cleaned dataset:

- Contains no invalid entries
- Has proper data types
- Is ready for analysis and visualization
