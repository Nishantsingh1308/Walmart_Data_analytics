# Walmart_Data_analytics
A walmart business inteleeginent data analytics project created on power bi that helps in analysis of business trend

# Power BI Dashboard Project

## 📌 Project Overview
This project demonstrates end-to-end Power BI development:
- Importing & Cleaning data
- Building Data Model
- Creating Visualizations
- Adding Interactivity
- Using DAX formulas
- Dashboard Formatting & Theming

---

## 🔹 Steps Implemented

### 1. Data Import & Cleaning
- Connected dataset (`Excel/CSV`).
- Cleaned data in Power Query:
  - Removed duplicates
  - Filtered invalid rows
  - Changed data types
  - Renamed columns

### 2. Data Modeling
- Used **2+ related tables**.
- Defined relationships for proper star schema.

### 3. Visualizations (at least 5)
- Column/Bar Chart → Sales by Region  
- Table/Matrix → Customer details  
- Card → KPIs (Total Sales, Avg Age)  
- Pie/Donut Chart → Gender/Department Distribution  
- Line Chart → Monthly Trends  

### 4. Interactivity
- Added **Slicers** (Year, Department, Region, Gender).  
- Drill-down enabled on Sales by Year → Month.  
- Cross-filtering works across visuals.  

### 5. Basic DAX
- **Calculated Columns**
  - `Profit = Sales – Cost`
  - `Pass_Fail = IF([Sales] > [Cost], "Pass", "Fail")`

- **Measures**
  - `Total Sales = SUM(Sales[Amount])`
  - `Average Age = AVERAGE(Customers[Age])`

### 6. Dashboard Formatting
- Applied a professional theme.  
- Added **titles & sections** using text boxes and shapes.  
- Inserted company logo (`assets/logo.png`).  

---

## 📂 Files
- `dataset/` → Raw dataset files  
- `powerbi_files/` → Final `.pbix` Power BI dashboard file  
- `docs/` → Step-by-step documentation  
- `assets/` → Images and logo  

---

## 🚀 How to Use
1. Download dataset from `dataset/`.
2. Open `Dashboard.pbix` in Power BI Desktop.
3. Explore visuals, slicers, and interactivity.
