# Task 1 – Data Cleaning and Preprocessing

## Objective

The objective of this task was to clean and preprocess the Customer Personality Analysis dataset using Python and Pandas.

## Dataset

**Customer Personality Analysis**

The dataset contains customer demographic, purchasing, and campaign-related information.

## Tools Used

* Google Colab
* Python
* Pandas
* NumPy
* GitHub

## Data Cleaning Performed

The following steps were performed:

1. Loaded the raw dataset using Pandas.
2. Inspected the dataset structure, columns, and data types.
3. Identified missing values using `isnull()`.
4. Checked for duplicate records using `duplicated()`.
5. Removed duplicate records using `drop_duplicates()`.
6. Standardized column names by converting them to lowercase and replacing spaces with underscores.
7. Handled missing values in the `income` column using the median.
8. Standardized text values in the education and marital status columns.
9. Converted the customer date column to datetime format.
10. Checked numerical data types.
11. Inspected numerical variables for unusual values.
12. Performed final data quality checks.
13. Saved the cleaned dataset as `cleaned_dataset.csv`.

## Repository Structure

```text
Task-1-Data-Cleaning/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── screenshots/
│
├── Task-1-Data-Cleaning.ipynb
│
└── README.md
```

## Result

The raw dataset was cleaned by handling missing values, removing duplicate records, standardizing text and column names, converting dates, checking data types, and performing data quality checks.

The resulting cleaned dataset is ready for further analysis and visualization.

## Conclusion

This task provided practical experience in identifying and resolving common data quality issues using Python and Pandas.
