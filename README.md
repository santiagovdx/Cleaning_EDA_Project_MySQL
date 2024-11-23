# SQL Cleaning and Exploratory Data Analysis (EDA) Project

This project showcases the process of cleaning and performing exploratory data analysis (EDA) on the `world_layoffs` dataset using SQL.

## Overview
The primary goals of this project were:
- Removing duplicates
- Standardizing data (text formatting, date formats, etc.)
- Handling NULL and blank values
- Preparing the dataset for downstream analysis

## Key Features
- **SQL Techniques Used:** 
  - CTEs (Common Table Expressions)
  - Window Functions
  - Data Standardization (e.g., trimming, case updates, date transformation)
  - Conditional Updates with `CASE`
  - Dealing with NULL values effectively
  - Auto-Increment ID usage for unique identification
  - Use of transactions for secure updates
  
- **Dataset:** Layoffs data including company information, industry, location, and dates.

## Folder Structure
- `sql/`: Contains the SQL script used for cleaning and EDA.
- `notes/`: Descriptive notes explaining the thought process and key decisions.
- `screenshots/`: Optional visuals or outputs from the SQL process.

## Running the Code
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SQL-Cleaning-EDA-Project.git
