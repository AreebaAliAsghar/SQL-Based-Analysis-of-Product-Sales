# 🗄️ SQL-Based Analysis of Product Sales  

## 🔍 Project Overview  
This project was completed **remotely at Elevvo Pathways** as part of my Data Analytics internship.  

It focuses on using **SQL queries** to analyze product sales from the **Chinook Database (Kaggle)**.  
The analysis answers critical business questions, such as identifying **top-selling products, revenue per region, and monthly performance trends**.  

By leveraging **JOINs, aggregations, and window functions**, this project transforms raw relational database tables into **actionable business insights**.  

---

## ⚙️ Workflow & Methodology  

### 1. Database & Setup  
- Used the **Chinook Database** containing information about customers, invoices, tracks, albums, and artists.  
- Loaded the dataset into **SQLite / PostgreSQL / MySQL** for SQL querying.  

### 2. SQL Analysis  
- **Top-Selling Products:** Identified best-selling tracks and albums based on revenue.  
- **Revenue by Region:** Aggregated invoices by customer country/region to analyze sales distribution.  
- **Monthly Performance:** Grouped invoice data by month/year to uncover seasonality trends.  
- **JOINs:** Combined multiple tables (e.g., `invoices`, `customers`, `tracks`, `albums`, `artists`) to build insights.  
- **Window Functions (Bonus):** Used `ROW_NUMBER()` and `RANK()` to rank products by revenue and performance.  

---

## 📊 Tools & Libraries  
- **SQL:** SQLite / PostgreSQL / MySQL / BigQuery  
- **Python (Optional):** pandas, sqlite3/SQLAlchemy for database connection and query execution  
- **Jupyter Notebook:** For query documentation and explanation  

---

## 📌 Example Business Questions Answered  
✔️ What are the **top-selling tracks and albums** by revenue?  
✔️ Which **regions/customers contribute the most sales**?  
✔️ How do **monthly sales trends** look across years?  
✔️ Who are the **top 5 customers** based on total purchases?  
✔️ What is the **revenue share of different genres/artists**?  

