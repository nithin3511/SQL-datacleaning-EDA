# SQL-datacleaning-EDA
SQL Data Cleaning & Exploratory Data Analysis on Layoffs Dataset
📌 Project Overview

This project demonstrates an end-to-end SQL workflow using a real-world layoffs dataset. The project is divided into two major phases:

Data Cleaning
Exploratory Data Analysis (EDA)

The objective is to transform raw data into a clean and analysis-ready dataset, then uncover business insights using SQL.

🛠️ Tools Used
MySQL
SQL Window Functions
Common Table Expressions (CTEs)
Aggregate Functions
Data Cleaning Techniques
Exploratory Data Analysis
📂 Project Files
File	Description
layoffs.csv	Raw layoffs dataset
Data Cleaning Project.sql	SQL script for cleaning and preparing data
Exploratory Data Analysis.sql	SQL script for analyzing layoffs trends
🧹 Data Cleaning Process
1. Created Staging Tables
Created duplicate tables to preserve raw data.
Used staging tables for transformations.
2. Removed Duplicate Records
Applied ROW_NUMBER() window function.
Identified and deleted duplicate entries.
3. Standardized Data
Trimmed extra spaces from company names.
Standardized industry values (e.g., Crypto categories).
Fixed country name inconsistencies.
4. Converted Data Types
Converted date columns into proper SQL DATE format.
5. Handled Missing Values
Replaced missing industries using self-joins.
Removed records with insufficient information.
6. Final Data Preparation
Removed helper columns used during cleaning.
Generated a clean dataset ready for analysis.
📊 Exploratory Data Analysis (EDA)
Business Questions Answered
Company Analysis
Which companies had the highest layoffs?
Average layoff percentage by company.
Industry Analysis
Industries most affected by layoffs.
Industry-wise layoff distribution.
Country Analysis
Countries with the highest layoffs.
Time-Series Analysis
Layoffs by year.
Monthly layoff trends.
Rolling cumulative layoffs over time.
Funding & Business Stage Analysis
Companies with 100% workforce layoffs.
Impact of funding and company stage on layoffs.
Ranking Analysis
Top 5 companies with the highest layoffs each year using DENSE_RANK().
📈 Key SQL Concepts Demonstrated
Data Cleaning
TRIM()
UPDATE
DELETE
ALTER TABLE
STR_TO_DATE()
Data Analysis
GROUP BY
ORDER BY
Aggregate Functions (SUM, AVG, MAX, MIN)
Window Functions
CTEs
Ranking Functions (ROW_NUMBER, DENSE_RANK)
🎯 Skills Demonstrated
SQL Data Cleaning
Data Transformation
Data Validation
Exploratory Data Analysis
Business Insight Generation
Window Functions
Advanced SQL Querying
📷 Sample Insights
Identified companies with complete workforce reductions.
Tracked yearly and monthly layoff trends.
Ranked top companies by layoffs each year.
Measured industry and country-level impact.
