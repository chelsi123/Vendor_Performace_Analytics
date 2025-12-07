# 📦 Vendor Performance Analytics Project

## 📌 Project Overview
Vendor Performance Analytics is an end-to-end data analytics project designed to evaluate vendor efficiency, profitability, purchase behavior, and sales performance.  
The project demonstrates real-world skills across the full data lifecycle — including **data extraction**, **cleaning**, **SQL (DuckDB)**, **EDA**, and **interactive dashboard creation** using Power BI.

This project showcases:
- Data engineering & transformation  
- Exploratory Data Analysis (EDA)  
- Business KPI development  
- Dashboard design & insight storytelling  

---


---

## 📁 Raw Data Access
The raw datasets used in this project are available here:

🔗 **Google Drive (Raw Data Folder):** *https://drive.google.com/drive/folders/1XomfEE819R8WCZt_snisPzbQzO4_3N-i?usp=sharing*



---

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **DuckDB SQL** (in-notebook querying)  
- **Power BI Desktop**  
- **Google Colab**  

---

## 📝 1. Data Extraction & Cleaning
Notebook: **`Data_Extraction_and_Preparation.ipynb`**


This notebook prepares all data for the Vendor Performance Analytics project. It:

- Connects to DuckDB and loads raw CSVs (purchases, sales, vendor_invoice, purchase_prices)
- Cleans data (missing values, whitespace, data types)
- Computes key vendor metrics:  
  Total Purchase/Sales Qty & Dollars, Excise Tax, Freight Cost, Gross Profit, Profit Margin, Stock Turnover, Sales-to-Purchase Ratio
- Creates the final **vendor_sales_summary** table by merging purchase, sales, and freight data
- Exports the summary CSV for use in EDA and Power BI

**Technologies:** Python, DuckDB/SQL, Pandas  
**Output:** `vendor_sales_summary` — the core dataset for the full analysis.

---

## 📊 2. Exploratory Data Analysis (EDA)
Notebook: **`Vendor_Performance_EDA_and_Insights.ipynb`**

Analytical work includes:


- Data loading, cleaning, and handling zero/invalid values  
- Descriptive statistics and outlier detection  
- Distribution analysis (histograms, boxplots)  
- Vendor and brand performance insights  
- Correlation analysis across sales, quantity, margins, and profitability  
- Ranking top and low-performing vendors/brands  
- Profit margin analysis with 95% confidence intervals  
- Two-sample t-test comparing profit margins of top vs. low-performing vendors  

This notebook transforms the cleaned dataset into actionable insights for business decision-making.
---

## 📈 3. Power BI Dashboard
File: **`Vendor_performance_dashboard.pdf`**



This dashboard provides a complete view of vendor, brand, and purchase performance using DAX measures, calculated tables, and visual insights.

### 🔢 Key KPIs (DAX)
- Total Sales ($)
- Total Purchase ($)
- Gross Profit ($)
- Profit Margin (%)
- Unsold Capital ($)

### 📦 Purchase Contribution
- Created a `PurchaseContribution` table   
- Calculated PurchaseContribution%  column using DAX
- Visualized **Top 10 Vendors by Purchase Contribution%**

### 💰 Sales Insights
- Bar charts for **Top 10 Vendors by Sales**  
- Bar charts for **Top 10 Brands by Sales**

### 🏷️ Brand Performance
- Created Brand Performance table  
- Added `TargetBrand` column using DAX  
- Scatter plot to identify brands needing promotional/pricing action

### 🎯 Bulk Purchasing Impact
- DAX columns for `Order Size` and `Unit Purchase Price`  
- Donut chart to show how bulk purchasing affects unit price

### 📉 Low Stock Turnover Vendors
- Created `LowTurnoverVendor` table  
- Column chart highlighting low-performing vendors by StockTurnOver

This dashboard delivers clear, actionable insights into vendor profitability, brand performance, and purchasing efficiency.




---

## 🔍 Key Insights


- Profit margin showed a **slight negative correlation** with sales price.  
- Strong relationship between **purchase quantity and sales quantity**.  
- Significant variation in **unit purchase price based on order size**.  
- Identified a set of vendors consistently generating low profit margins.  

---

## 🚀 How to Run This Project
1. Download raw data (optional).  
2. Run `Data_Extraction_and_Preparation.ipynb` to generate cleaned data.  
3. Run Vendor_Performance_EDA_and_Insights.ipynb` for insights & visualizations.  
4. Open the Vendor_performance_dashboard.pdf to explore interactive analytics.  

---

## 👩‍💻 Author
This project was created to demonstrate end-to-end skills in data cleaning, SQL-based analysis, exploratory analytics, and dashboard storytelling for business decision-making.

---

