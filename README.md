# Layoffs-Data-Cleaning-Project-In-MySQL

# 🚀 Layoffs Data Cleaning Project in MySQL 🧹

## 🔍 Project Overview
This project focuses on cleaning and preparing layoffs data in MySQL to convert raw data into a clean, reliable, and analysis-ready dataset.  
Key tasks include removing duplicates, standardizing data, and handling missing or inconsistent entries.

---

## 🎯 Key Tasks
- 🧮 Remove duplicates using `ROW_NUMBER() OVER (PARTITION BY ...)`  
- ✂️ Trim whitespace with `TRIM()`  
- 🔤 Standardize text casing via `UPPER()` / `LOWER()`  
- 📅 Convert string dates using `STR_TO_DATE()`  
- ❓ Handle missing/null values with `IS_NULL()` or `IS NULL` checks  

---

## 🛠️ SQL Functions Used
| Function                       | Purpose                                      |  
|-------------------------------|----------------------------------------------|  
| `TRIM()`                      | Removes leading/trailing spaces               |  
| `UPPER()` / `LOWER()`          | Converts text to uppercase or lowercase      |  
| `STR_TO_DATE()`                | Converts string to MySQL `DATE` format       |  
| `ROW_NUMBER() OVER (PARTITION)`| Helps identify duplicate rows by partition  |  
| `IS_NULL()` / `IS NULL`        | Checks and manages null/missing values        |  

---

## 🧹 Data Cleaning Steps
1. 📥 Load raw layoffs data into a staging table  
2. 🆔 Identify and remove duplicates with window functions  
3. ✂️ Standardize text with trimming and casing  
4. 📆 Convert text-based dates to proper date formats  
5. ⚠️ Handle or remove null or inconsistent entries  
6. 🔎 Clean up redundant columns/rows for analysis readiness  

---

## 🚀 Usage  
Run the SQL scripts sequentially to replicate the data cleaning workflow. Update column names to suit your dataset.

---

## 📬 Contact  
Maintainer: Abhijith   
Date: November 2025 
