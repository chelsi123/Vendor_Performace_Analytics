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

🔗 **Google Drive (Raw Data Folder):** *(https://drive.google.com/drive/folders/1DHnYXDKghQZRn6Et9kQCI4WXeskXYzWh?usp=drive_link)*



---

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **DuckDB SQL** (in-notebook querying)  
- **Power BI Desktop**  
- **Google Colab**  

---

## 📝 1. Data Extraction & Cleaning
Notebook: **`Data_Extraction_and_Preparation.ipynb`**

Key steps performed:
- Loaded raw vendor-related datasets  
- Cleaned missing values and duplicates  
- Standardized numeric fields  
- Performed SQL joins & transformations using **DuckDB**  
- Created the final analytical dataset: **`vendor_sales_summary`**  
- Prepared data for EDA and dashboard development  

---

## 📊 2. Exploratory Data Analysis (EDA)
Notebook: **`Vendor_Performance_EDA_and_Insights.ipynb`**

Analytical work includes:
- Distribution analysis of sales, purchase amounts, profit, and quantities  
- Boxplots for outlier detection  
- Correlation analysis (price, sales, margins, inventory movement)  
- Scatter plots for trend discovery  
- Order size segmentation  
- Pareto (80/20) vendor contribution insights  
- Summary statistics & comparative vendor performance  

---

## 📈 3. Power BI Dashboard
File: **`Vendor_performance_dashboard.pdf`**

Interactive dashboard highlights:
- Top-performing vendors  
- Revenue & profit trends  
- Profit margin insights  
- Vendor segmentation  
- Purchase vs Sales behavior  
- Inventory turnover  
- Low-performing vendor alerts  



---

## 🔍 Key Insights
(Replace with your actual results; example insights below.)

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

