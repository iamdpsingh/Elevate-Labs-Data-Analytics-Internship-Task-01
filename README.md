# Elevate-Labs-Data-Analytics-Internship-Task-01
Task 1 - Data Cleaning and Preprocessing

## Task Overview
This repository contains a step-by-step guide for cleaning and preprocessing raw data to prepare it for analysis or machine learning tasks. The goal is to transform messy, unstructured data into clean, usable datasets by handling missing values, correcting inconsistencies, and transforming features into usable formats.

## Data Cleaning Process
### 1. **Handling Missing Data**
   - **Identifying Missing Values**: Used Pandas to detect missing values (NaN) in the dataset.
   - **Dropping**: In cases where there were too many missing values in a column or row, I dropped them.

### 2. **Removing Duplicates**
   - Checked for duplicate entries in the dataset and removed them using `drop_duplicates()` in Pandas.

### 3. **Correcting Data Types**
   - Converted date columns into datetime format using `pd.to_datetime()`.

### 4. **Standardizing Categorical Data**
   - Ensured categorical values had consistent formats (e.g., fixing typos, normalizing case).
   - For example, all values in a column that describe the “gender” of a person were standardized to `Male/Female` format.


## Technologies Used
- **Python** (for data cleaning and preprocessing)
- **Pandas** (for data manipulation)

