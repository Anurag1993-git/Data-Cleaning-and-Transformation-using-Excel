#  Data Cleaning & Transformation with Excel (Sales 1997-1998)

This project focuses on cleaning, transforming, and preparing raw sales data from 1997 and 1998 for analysis and dashboarding. The dataset includes **Customers**, **Products**, **Regions**, **Sales**, **Returns**, and **Transactions**. The final cleaned data is ready for analysis in Excel, Power BI, or other BI tools.

---

##  Project Overview

The raw dataset contained inconsistencies like:
- Duplicate customer and product entries
- Missing values in critical columns
- Non-standard date formats
- Multiple datasets for 1997 and 1998

The goal was to:
1. **Clean and merge all datasets**  
2. **Standardize fields (Customers, Products, Regions)**  
3. **Create calculated fields (Revenue, Net Sales, Return Rate)**  
4. **Prepare power-query tables** for further visualization

---

##  Datasets Used

- **Customers**: Customer_ID, Customer_Name, Region_ID
- **Products**: Product_ID, Product_Name, Category, Unit_Price
- **Regions**: Region_ID, Region_Name, Country
- **Sales**: Transaction_ID, Date, Customer_ID, Product_ID, Quantity, Unit_Price
- **Returns**: Return_ID, Transaction_ID, Date, Reason
- **Transactions**: Combined 1997 & 1998 sales transactions

---

## Tools & Techniques

- **Microsoft Excel**:
  - Data Cleaning: `TRIM()`, `CLEAN()`, `PROPER()`
  - Data Validation & removing duplicates
  - Date extraction: `YEAR()`, `MONTH()`, `TEXT()'
  - Calculated columns: `Revenue = Quantity * Unit_Price`
  - Pivot table preparation
- **Data Merging**: 1997 & 1998 sales data combined into a single table with `Year` column
- **Return Analysis**: `Return Rate = Returned_Units / Total_Units`

---

## Data Cleaning Steps

1. **Standardized headers** (removed spaces, used underscores)
2. **Removed duplicates** in Customers and Products tables
3. **Fixed missing values** using replacements or logical estimates
4. **Formatted dates** into `YYYY-MM-DD` format
5. **Merged 1997 and 1998 sales files** into one dataset
6. **Joined lookup tables** (Customer & Product details into Sales table)
7. **Calculated columns** for:
   - Revenue
   - Net Sales (`Revenue - Returns`)
   - Return Rate
8. **Prepared pivot-ready tables** for dashboarding

---

## Key Outputs

- **Cleaned data tables** ![Data Cleaned and Transformed](`<img width="795" height="400" alt="Data Cleaning and Data Transformation outcome of sales e-commerce" src="https://github.com/user-attachments/assets/f9ce694e-bee9-4746-9671-5c0f27035d82" />
`)
- **Pivot-ready dataset** for dashboarding
- **Summary reports** for 1997 & 1998 sales performance
- **Return trends analysis**

---

## Folder Structure
Data Cleaning and Transformation/
├── Sales Dataset/
│   ├── customers.xlsx
│   ├── products.xlsx
│   ├── regions.xlsx
│   ├── sales_1997.xlsx
│   ├── sales_1998.xlsx
│   ├── returns.xlsx
│   └── transactions_cleaned.xlsx
├── images/ (Cleansed_Power_Query_Sales_Data)
│   └── ('<img width="1129" height="485" alt="Cleansed_Power_Query_Sales_Data" src="https://github.com/user-attachments/assets/e043f88b-91b6-41c5-a040-3a3be32e0b12" />
')
└── README.md

 ## About Me
 Anurag – Aspiring Data Analyst
 email: anuragkdataanalyst@gmail.com
 LinkedIn: https://www.linkedin.com/in/anuragkaushik-analytics/
 Portfolio: https://www.datascienceportfol.io/anuragkaushik867


