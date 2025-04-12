🧹 # Data Cleaning
Data cleaning is a crucial step in any data science or analytics project. This section describes the preprocessing and cleaning techniques applied to the Additional ,data,customers and players data to ensure data quality, consistency, and usability for analysis and modeling.

🔍 Objectives
Handle missing, inconsistent, or duplicate data

Normalize categorical values

Convert data types where necessary

Ensure the dataset is ready for EDA, visualization, and modeling

🧼 Cleaning Steps
Handling Missing Values

Checked for null or missing values in each column

Imputed missing numerical values using mean/median

Imputed categorical missing values using the most frequent value (mode)

Removing Duplicates(e.g.,sample["Sales Rep"].drop_duplicates(inplace=True))

Removed exact duplicate rows to avoid redundancy

Standardizing Column Formats

Converted column names to fullname for consistency (e.g., player["name"]=player["name"].replace(to_replace="V Kohli",value="Virat kohli")

Data Type Conversion

Converted categorical columns to proper category data types

Ensured numeric columns were in int or float format as required

Encoding Categorical Variables

Attrition Column Cleanup

Standardized binary target values: 'Yes' and 'No' converted to 1 and 0

✅ Result
After cleaning, the dataset is free from missing values, inconsistencies, and formatting issues. It is now suitable for:

Exploratory Data Analysis (EDA)

Visualization

Machine Learning model building
