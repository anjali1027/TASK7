# Sales Data Analysis - Task 7

## 📋 Project Overview
This project demonstrates basic sales data analysis using Python, SQLite, and data visualization. Created as part of a Data Analyst internship task.

## 🎯 Objective
- Connect Python to a SQLite database
- Execute SQL queries to analyze sales data
- Create visualizations using matplotlib
- Generate sales summary reports

## 🛠️ Technologies Used
- **Python 3.x**
- **SQLite3** (built into Python)
- **Pandas** (data manipulation)
- **Matplotlib** (data visualization)

## 📁 Files in this Repository
- `sales_analysis.py` - Main Python script containing all analysis code
- `sales_data.db` - SQLite database file (created when script runs)
- `sales_chart.png` - Generated visualization charts
- `README.md` - This documentation file



## 📊 What the Script Does

### 1. Database Creation
- Creates a SQLite database (`sales_data.db`)
- Creates a `sales` table with columns: id, product, quantity, price, sale_date
- Populates with **100 sample sales records** across 20 different products
- Data spans 3 months (January to March 2024)

### 2. Data Analysis
Executes two main SQL queries:

**Query 1: Sales Summary by Product**

**Query 2: Overall Totals**


### 3. Visualization
- Creates bar charts showing:
  - **Top 10 Products** by Revenue
  - **Top 10 Products** by Total Quantity Sold
- Saves charts as `sales_chart.png`

### 4. Additional Insights
- Monthly sales trends analysis
- Product performance metrics
- Transaction frequency analysis



## 🔍 Key Learning Points

1. **Database Connection**: Using `sqlite3.connect()` to connect Python to SQLite
2. **SQL Queries**: Writing GROUP BY queries for data aggregation
3. **Pandas Integration**: Using `pd.read_sql_query()` to load SQL results
4. **Data Visualization**: Creating bar charts with matplotlib
5. **Revenue Calculation**: Using `SUM(quantity * price)` in SQL


## 🎉 Results
- Successfully created and queried SQLite database with **100 records**
- Generated comprehensive sales analysis across **20 product categories**
- Created professional visualizations showing **top 10 performers**
- Demonstrated end-to-end data pipeline from database to insights
- Added monthly trends and performance metrics analysis

## 👨‍💻 Author
Created by ANJALI ANGADALA
