# Excel_Assignment_2_Data_Cleaning_and_Transformation

## Objective

To clean, transform, and format a product dataset using Microsoft Excel.

## Methods Used

### 1. Handling Missing Values
- Used the **median method** to impute missing values in the Price column.
- Used product information and existing patterns in the dataset to determine missing Category values.

### 2. Correcting Inconsistent Data
- Used the **PROPER()** function to standardize Product Name capitalization.
- Used **Find & Replace** to correct inconsistent Category values such as "Electroni to Electronic"

### 3. Removing Duplicates
- Used Excel's **Remove Duplicates** feature.
- Selected all columns so duplicate rows were identified based on the entire row.

### 4. Splitting and Merging Data
- Used **LEFT()** and **DATEVALUE()** to extract and convert the Manufacturing Date.
- Used **RIGHT()** to extract the Country Code from the Product ID.
- Added the year **2026** to the Manufacturing Date.
- Used the **&** to merge Brand Name and Product Name into Product Brand.

### 5. Number Formatting
- Formatted the Price column as currency.
- Formatted the Manufacturing Date as DD-MM-YYYY.

### 6. Conditional Formatting
- Applied **Data Bars** to the Price column.
- Created a conditional formatting rule to highlight cells containing **Electronics** in the Category column.

## Tools Used

- Microsoft Excel

## Screenshot

![Excel Assignment 2 Screenshot](Assignment_2_Screenshot.png)
