# Superstore-Data-Cleaning-and-Preprocessing

Description: Cleaned and preprocessed a superstore sales dataset to ensure data consistency, accuracy, and readiness for further analysis, focusing on missing values, incorrect data types, and data validation.

Loaded the dataset into a pandas DataFrame and performed exploratory checks using df.info() and df.isnull().sum() to identify data quality issues.

Removed records with missing CustomerID entries and corrected negative values in Quantity and Sales fields by converting them to absolute values.

Filtered out rows with zero UnitPrice to maintain valid sales data.

Converted InvoiceDate to a proper datetime format for time-based analysis and reporting.

Exported the cleaned dataset to a new CSV file for downstream analysis and visualization.

Tech Stack: Python, pandas
