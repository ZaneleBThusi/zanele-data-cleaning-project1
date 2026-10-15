# Project 1: School Learner Data Cleaning

### 👩‍💻 Author: Zanele Boitumelo Thusi
### 📍 Location: Sasolburg, South Africa
### 🛠 Tools: Google Sheets, Microsoft Excel

### 📖 Project Description
Cleaned a messy school learner dataset with 10+ records to prepare it for analysis. This project demonstrates core data analyst skills in data quality and standardization.

### 📂 File in this Repo
- `Zanele_Data_Cleaning_Project1.xlsx` - Contains:
    - `Sheet1` - Raw / Dirty data
    - `Final_Clean` - Cleaned, analysis-ready data

### 🐛 Dirty Data Found
- Duplicate Learner_IDs
- Inconsistent name casing (john, THABO, thusi)
- Inconsistent date formats (2024/01/15 vs 2024-01-15 vs 15-Jan-2024)
- Invalid scores (101% for Amogelang)
- Blank / "Unknown" rows

### ✅ Cleaning Steps Applied
1.  Used `TRIM()` to remove extra spaces from names
2.  Used `PROPER()` and `UPPER()` to standardize casing (e.g., Zanele Thusi)
3.  Standardized all dates to `YYYY-MM-DD` format
4.  Corrected invalid score 101% → 75% (data quality decision)
5.  Removed duplicate and unknown rows
6.  Created `Final_Clean` sheet with Paste Special > Values Only
7.  Added `Clean_Name`, `Clean_Surname`, `Clean_Score` columns

### 🎯 Skills Demonstrated
- Data Cleaning & Data Quality
- Google Sheets Formulas (TRIM, PROPER, UPPER)
- Data Standardization
- Attention to Detail
- Portfolio Building with Excel & GitHub

### 🔗 Portfolio
First project in my Data Analyst journey - October 2026
