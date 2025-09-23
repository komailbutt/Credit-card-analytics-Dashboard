# 📊 Credit Card Financial Dashboard (Weekly Report)

## 📌 Project Overview
This project focuses on building a **Credit Card Financial Dashboard** that delivers real-time insights into key performance metrics and trends.  
The dashboard enables stakeholders to effectively monitor and analyze credit card operations, customer behavior, and financial performance.  

The workflow uses **PostgreSQL (via pgAdmin 4)** for database setup, and **Power BI with DAX** for all data preprocessing, transformations, and visualizations.  

📌 **Note:**  
- `cc_add.csv` contains additional credit card transaction entries used to test **real-time refresh** in Power BI.  
- `cust_add.csv` contains additional customer entries used to test **real-time refresh** in Power BI.  

---

## 🎯 Objectives
- Create a structured database for financial and customer data  
- Build an interactive Power BI dashboard with advanced DAX measures  
- Monitor weekly and year-to-date (YTD) credit card performance  
- Provide actionable insights for business decision-making  

---

## 🛠️ Tech Stack & Tools
- PostgreSQL – Database creation and management  
- pgAdmin 4 – GUI tool for PostgreSQL queries and imports  
- Power BI – Dashboard design, data preprocessing, and visualization  
- DAX – Custom measures and KPIs (Revenue, Weekly Change, Age/Income Groups, etc.)  
- CSV Data Files – Input data for loading into the database  

---

## 📂 Project Workflow
### 1. Database Setup (PostgreSQL & pgAdmin 4)
- Create a database (`ccdb`) and tables (`cc_detail`, `cust_detail`)  
- Import raw data from CSV files into the tables  

### 2. Data Modeling & Transformation (Power BI)
- Import SQL tables into Power BI  
- Create calculated columns and measures using DAX  
- Handle preprocessing (grouping, aggregations, KPI creation)  

### 3. Dashboard Development
- Design an interactive dashboard with slicers and visuals  
- Track revenue growth, customer demographics, card categories, and delinquency  

### 4. Insights & Reporting
- Compare current vs. previous week performance  
- Generate year-to-date business insights  

---

## 📊 Key Insights (Sample)
- 📈 Revenue increased by **28.8% (WoW)**  
- 💳 Overall revenue: **$57M** | Interest Earned: **$8M** | Transactions: **$46M**  
- 👨‍💼 Male customers contribute **$31M**, while female customers contribute **$26M**  
- 💠 Blue & Silver credit cards account for **93% of transactions**  
- 🏙️ Top 3 states (TX, NY, CA) contribute **68% of revenue**  
- ✅ Activation Rate: **57.5%** | ⚠️ Delinquency Rate: **6.06%**  

---

## ✅ Summary
This project demonstrates:
- Structuring and loading raw CSV data into PostgreSQL  
- Using additional CSV files to test **real-time refresh** in Power BI  
- Applying DAX in Power BI for transformations and KPIs  
- Designing an interactive dashboard for weekly & YTD monitoring  
- Extracting actionable business insights for stakeholders  
