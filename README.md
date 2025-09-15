# 🏡 Nashville Housing Data Cleaning & Analysis (SQL Project)  

**Date:** Sept 2025  

## 📌 Project Overview  
This project is a **SQL-based data cleaning and transformation** exercise using the Nashville Housing dataset.  

The goal was to **standardize and prepare raw housing transaction data** so it could be reliably used for **business analysis, forecasting, and reporting**.  

This project demonstrates my ability to:  
- Apply **SQL techniques for data cleaning and normalization**  
- Standardize inconsistent formats (dates, addresses, categorical fields)  
- Handle missing values and duplicates to improve data quality  
- Prepare datasets for **business intelligence and decision-making**  

---

## 🛠 Tools & Skills Used  
- **SQL (SSMS)**  
  - Joins & subqueries  
  - String functions (SUBSTRING, CHARINDEX, PARSENAME, REPLACE)  
  - Data type conversions (CAST/CONVERT)  
  - Window functions (ROW_NUMBER) for deduplication  
- **Data Cleaning & Transformation**  
  - Standardizing date and address formats  
  - Handling NULLs with relational lookups  
  - Converting categorical inconsistencies (e.g., “Y/Yes” → Yes)  
  - Removing duplicate transactions  

---

## 📊 Key Insights  
- **Address Standardization:** A significant share of property addresses required backfilling or restructuring to enable neighborhood-level analysis.  
- **Vacancy Status:** Inconsistent values (“Y”, “Yes”, “N”, “No”) were standardized to **Yes/No**, improving reporting accuracy.  
- **Duplicates:** Identified and removed duplicate property sales, ensuring unique transaction counts.  
- **Owner Information:** Split owner address fields into **Street, City, and State**, making the dataset more usable for geographic analysis.  

---
