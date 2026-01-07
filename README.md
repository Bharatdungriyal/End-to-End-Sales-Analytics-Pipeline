# 🚀 End-to-End Sales & Customer Analytics Data Pipeline

## 📌 Project Description
This project demonstrates a **complete end-to-end Sales & Customer Analytics data pipeline**, starting from raw data ingestion to business-ready executive dashboards.  
It closely mirrors **real-world corporate MIS (Management Information System) dashboards** used by analytics and finance teams for decision-making.

The project integrates **Python, SQL, and Power BI** to perform data extraction, transformation, loading (ETL), dimensional modeling, and interactive reporting.

---

## 🏆 Why This Project Is Valuable
- Implements a **full ETL pipeline**
- Combines **SQL + Python + Power BI**
- Uses **industry-standard dimensional modeling (Star Schema)**
- Simulates **corporate MIS and executive dashboards**
- Includes **business KPIs and profitability analysis**
- Implements **basic Row-Level Security (RLS)**

---

## 🧱 Tech Stack
- **Data Source:** Kaggle (CSV files)
- **Programming:** Python (Pandas, SQLAlchemy)
- **Database:** MySQL / PostgreSQL
- **Data Modeling:** Fact & Dimension tables (Star Schema)
- **Visualization:** Power BI
- **Version Control:** Git & GitHub

---

## 📊 Dataset
- Sales transactional data downloaded from **Kaggle**
- Format: CSV
- Domain: Retail / Sales Analytics

---

## 🛠️ Project Workflow (Step-by-Step)

### 🔹 STEP 1: Raw Data Ingestion
- Downloaded raw CSV files from Kaggle
- Stored original data in a `raw_data` folder for traceability

**Deliverable:**
- Raw CSV files

---

### 🔹 STEP 2: Exploratory Data Analysis (EDA) – Python
Performed EDA using **Pandas** to:
- Understand data structure
- Identify missing values and duplicates
- Analyze sales, profit, and order distributions
- Validate date consistency

---

### 🔹 STEP 3: Data Cleaning & Transformation (Python)
Used **Pandas** to clean and standardize the dataset:

**Key Transformations:**
- Removed duplicate records
- Handled missing values
- Converted and standardized date columns
- Renamed columns to `snake_case`
- Created derived business metrics

**Deliverable:**
- Cleaned CSV files stored in `cleaned_data` folder

---

### 🔹 STEP 4: ETL Pipeline (Python)
Built an ETL pipeline using:
- **Pandas** for transformation
- **SQLAlchemy** for database connectivity

**ETL Features:**
- Extracted cleaned data
- Transformed data into fact and dimension tables
- Loaded data into a relational database
- Ensured data consistency and integrity

---

### 🔹 STEP 5: Database Design & Modeling (SQL)

Designed a **Star Schema** optimized for analytics.

**Fact Table:**
- `fact_orders`

**Dimension Tables:**
- `dim_customers`
- `dim_products`
- `dim_region`
- `dim_date`

**SQL Concepts Used:**
- Primary keys
- Foreign keys
- Indexes
- Referential integrity

**Deliverable:**
- SQL schema file

---

### 🔹 STEP 6: Power BI Data Modeling
- Imported SQL tables into Power BI
- Created relationships using **Star Schema**
- Built DAX measures for business KPIs
- Optimized model for performance and reporting

---

### 🔹 STEP 7: Row-Level Security (RLS)
- Implemented **basic RLS** to simulate real corporate access control
- Restricted data visibility based on roles/regions

---

## 📈 Power BI Dashboard Pages
The Power BI report contains the following pages:

1. **Sales Performance & Profitability Dashboard**
2. **EXECUTIVE SUMMARY (KPI VIEW)**
3. **SALES TREND & GROWTH**
4. **Sales Performance**
5. **REGIONAL ANALYSIS**

---

## 📊 Executive Summary (KPI View)
This page provides a high-level overview for stakeholders, including:
- Total Sales
- Total Profit
- Total Orders
- Profit Margin %
- Average Order Value
- Monthly Sales and Profit trends
- Year and Month slicers for dynamic analysis

---

---

## 🎯 Key Outcomes
- Built a **production-style ETL pipeline**
- Applied **dimensional data modeling**
- Developed **executive-level Power BI dashboards**
- Gained hands-on experience with **corporate MIS reporting**
- Enabled data-driven business insights

---

## 👤 Author
**Bharat Sharma**  
Data Analyst | Beginner Data Scientist  
Skilled in Python, SQL, Power BI, and Analytics Engineering

---

