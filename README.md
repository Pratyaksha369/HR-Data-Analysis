# HR-Data-Analysis

## Project Overview
This project focuses on analyzing an HR Analytics dataset. The goal is to clean, transform, and derive key insights from the data using MySQL.

The analysis includes cleaning up date formats, adding new columns for analysis, and extracting meaningful statistics such as employee age distribution, gender/race breakdowns, average employment duration, and yearly changes in employee count.

## Table of Contents
1. Dataset Description
2. Project Steps
3. Database and Table Creation
4. Data Cleaning and Transformation
5. Adding Age Column
6. Data Analysis and Insights
7. Insights Extracted

## Dataset Description
The dataset contains employee-related information such as:

1.Birthdate
2.Hire Date
3.Termination Date (term_date)
4.Gender
5.Race
6.Department

The dataset will be imported into a MySQL database for cleaning and analysis.

## Project Steps

### 1. Database and Table Creation
Database: Create a MySQL database called projects_hr.

Table: Create a table named hr based on the dataset's column headers.

Data Import: Import the HR Analytics dataset into the hr table.

### 2. Data Cleaning and Transformation

1.Standardize Date Formats
2.Convert Data Types
3.Handle NULL Values

### 3. Adding Age Column
Add a new column to calculate the current age of employees based on their birthdate.

### 4. Data Analysis and Insights
Perform queries and analysis to derive insights, including:

1.Youngest and Oldest Employees: Find the youngest and oldest employees and analyze age distribution.

2.Gender and Race Breakdown:
Breakdown of employees by gender.
Gender distribution by departments.
Employee distribution by race.
Average Employment Length: Calculate the average length of employment for all employees.
Yearly Change in Employee Count:
Analyze yearly hires and terminations.
Calculate the percentage change in employee count each year.
## Insights Extracted
1. Age Analysis
The youngest employee is 21 years old, and the oldest employee is 51 years old.
Employees can be grouped into various age categories for better analysis.
2. Gender and Race Analysis
Gender Breakdown: Total male and female employees.
Gender by Departments: Analyze the gender composition within each department.
Race Breakdown: Distribution of employees by race.

3. Employment Duration
The average length of employment is approximately 8 years.

4. Yearly Employee Trends

Calculate the yearly net change in employee count:
Despite fluctuations in hires and terminations, the workforce size remained relatively stable (ranging from 890 to 925 employees).
In 2007, the percentage change in employee count was slightly lower compared to previous years.
