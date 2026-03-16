# 📊 Excel Retail & Sales Analysis Project  
*A Data Technician Bootcamp Portfolio Project*

This project showcases a collection of Excel-based data analysis tasks completed during Week 1 of a Data Technician bootcamp. The work focuses on building strong foundational skills in spreadsheet analysis, data cleaning, transformation, and reporting using real retail and sales datasets.

---

## 📁 Project Overview

The project includes hands‑on exercises using **retail-sales**, **bike sales**, and **county-level product sales** datasets. Each task demonstrates practical Excel skills used by data technicians and analysts in real-world environments.

Key areas of focus:

- Data cleaning and preparation  
- Sorting, filtering, and conditional logic  
- Summary statistics using formulas  
- PivotTables and PivotCharts  
- Categorisation using the `SWITCH` function  
- Exploratory data analysis and insights generation  

---

## 🧮 Core Excel Skills Demonstrated

### **Formulas & Functions**
Used across multiple datasets to calculate totals, averages, lookups, and date-based values:

- **SUM**, **SUMIF** — calculating commissions and grouped totals  
- **AVERAGE**, **AVERAGEIF** — deriving mean values for specific conditions  
- **DATE**, **MONTH**, **YEAR** — extracting and manipulating date components  
- **UNIQUE** — identifying distinct values in large datasets  
- **VLOOKUP** — retrieving related information across tables  
- **SWITCH** — categorising sales volumes into *High*, *Medium*, and *Low* groups  

Example categorisation formula:

```excel
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
```

---

## 🔍 Data Preparation & Exploration

### **Filtering & Sorting**
- Sorted customer age data from *largest to smallest*  
- Applied filters to isolate specific customer groups  
- Cleaned and structured datasets for analysis  

### **Conditional Formatting**
- Highlighted high/low sales values  
- Identified outliers and trends visually  

---

## 📈 PivotTables & Visualisation

### **PivotTables**
Created multiple PivotTables to summarise:

- Sales by **county** and **product**  
- Bike sales by **country**, **gender**, and **age group**  
- Profitability across demographic segments  

These PivotTables enabled insights such as:

- Germany’s customers appear only in the *Adult (35–64)* market  
- Australia has sales across *all* markets  
- The *Adult* age group is the most profitable overall  

### **Charts & Visualisations**
- Built PivotCharts to visualise sales trends  
- Explored slicers and interactive filtering  
- Created dashboards for clearer storytelling  

---

## 🗂️ Project Files

This repository includes:

- Retail sales analysis workbook  
- Bike sales pivot table lab  
- County product sales dataset with SWITCH categorisation  
- Screenshots of PivotTables, charts, and formula outputs  
- A summary workbook documenting all tasks  

---

## 🧠 Key Learnings

- Strengthened confidence in Excel as a data analysis tool  
- Learned how to transform raw data into meaningful insights  
- Practised building dynamic reports using PivotTables and charts  
- Improved understanding of lookup functions and conditional logic  
- Gained experience categorising and segmenting data for reporting  
