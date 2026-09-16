# CODSOFT Data Analytics Internship

This repo has my work for Task 1, 2, and 3 of the CODSOFT Data 
Analytics Internship. I did all three tasks together in one Google 
Colab notebook using Python.

I used Seaborn's built-in "tips" dataset (restaurant billing data - 
total bill, tip, day, smoker/non-smoker, group size, etc.) since it 
was easy to load directly without downloading anything.

## Task 1: Data Cleaning
- Checked the dataset for missing values and duplicate rows
- Removed duplicates and fixed data types
- Saved the cleaned data as a new CSV file

## Task 2: Exploratory Data Analysis (EDA)
- Used describe() to get basic statistics of the data
- Checked correlation between total bill and tip
- Found outliers in the total bill column using IQR method
- Answered some business questions like which day has the highest 
  average bill, and if smokers tip more than non-smokers

## Task 3: Data Visualization
- Made 5 different charts using Matplotlib and Seaborn:
  - Bar chart (average bill by day)
  - Line chart (average tip by group size)
  - Pie chart (smoker vs non-smoker)
  - Histogram (total bill distribution)
  - Scatter plot (total bill vs tip)

## Tools Used
Python, Pandas, Seaborn, Matplotlib, Google Colab

## About
This was completed as part of the CODSOFT Data Analytics Virtual 
Internship.
