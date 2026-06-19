# SQL Layoffs Data Cleaning & Exploratory Data Analysis

## Project Overview
This project focuses on cleaning and analyzing a real-world layoffs dataset using SQL. The goal was to transform raw data into a clean, reliable dataset and then perform exploratory data analysis to identify trends, patterns, and business insights related to company layoffs.

## Dataset
- Source: Layoffs Dataset
- Format: CSV
- Records include company, industry, country, funding stage, total layoffs, percentage laid off, and date information.

## Data Cleaning Tasks
- Removed duplicate records using window functions.
- Standardized company, industry, and country names.
- Fixed inconsistent data formats.
- Converted date columns into proper SQL date format.
- Handled null and missing values.
- Removed unnecessary records and columns.

## Exploratory Data Analysis
The analysis answers questions such as:
- Which companies had the highest layoffs?
- Which industries were most affected?
- Which countries experienced the most layoffs?
- How did layoffs change over time?
- Which companies laid off 100% of their workforce?
- What were the yearly and monthly layoff trends?

## SQL Concepts Used
- CTEs (Common Table Expressions)
- Window Functions
- ROW_NUMBER()
- DENSE_RANK()
- Aggregate Functions
- GROUP BY & HAVING
- Joins
- Subqueries
- Date Functions

## Key Insights
- Identified the companies and industries most impacted by layoffs.
- Analyzed global layoff trends across multiple years.
- Ranked top companies by layoffs for each year.
- Calculated rolling monthly layoff totals.

## Files
- `layoffs.csv` – Raw dataset
- `Data Cleaning Project.sql` – Data cleaning queries
- `Exploratory Data Analysis.sql` – Analysis queries

## Skills Demonstrated
- SQL Data Cleaning
- Data Transformation
- Data Validation
- Exploratory Data Analysis (EDA)
- Business Insight Generation
- Advanced SQL Querying

## Author
Sai Nithin Reddy

GitHub: https://github.com/nithin3511
