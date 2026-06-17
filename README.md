# 🛒 Superstore Customer Details Dashboard
### End-to-End Data Analytics Project | Csv • Python • MySQL • Power BI

---

## 📌 Project Overview

This is a complete end-to-end data analytics project built on the popular **Superstore dataset**. The project covers the full data analytics workflow — from raw data ingestion and cleaning in Python, to advanced SQL analysis in MySQL, to an interactive business dashboard in Power BI.

---

## 🎯 Objective

To analyze Superstore sales, profit, customer, and shipping data in order to:
- Identify top-performing and underperforming product categories
- Understand regional and segment-wise sales trends
- Analyze customer behavior and order patterns
- Derive actionable business insights through visualization

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| **Python (Pandas)** | Data cleaning, preprocessing, EDA |
| **Jupyter Lab** | Development environment for Python |
| **MySQL** | Data storage and advanced SQL analysis |
| **Power BI** | Interactive dashboard and data visualization |
| **MySQL Connector/NET** | Power BI to MySQL connectivity |

---

## 📂 Project Structure

```
Superstore-Customer-Details-Dashboard/
│
├── 📄 README.md                    # Project documentation
├── 📊 Superstoredata.csv           # Raw dataset (9,994 records)
├── 📓 Myworking.ipynb              # Python data cleaning notebook
├── 🗄️ NEW_FILE SQL.sql             # MySQL analysis queries
├── 📊 SuperstoreDashboard.pbix     # Power BI dashboard file
└── 🖼️ dashboard_screenshot.png     # Dashboard preview
```

---

## 📊 Dataset Description

- **Source:** Superstore Sales Dataset
- **Records:** 9,994 rows | 23 columns
- **Key Columns:** `order_id`, `order_date`, `ship_date`, `ship_mode`, `customer_name`, `segment`, `region`, `city`, `state`, `category`, `sub_category`, `product_id`, `sales`, `profit`, `discount`, `quantity`

---

## 🐍 Phase 1: Data Cleaning (Python + Pandas)

**File:** `Myworking.ipynb`

Key steps performed:
- Loaded raw CSV data using Pandas
- Inspected dataset using `df.info()`, `df.describe()`, `df.shape`
- Handled null values and duplicate records
- Fixed data types (dates, numeric columns)
- Created derived columns for analysis
- Exported cleaned data to MySQL using SQLAlchemy

---

## 🗄️ Phase 2: SQL Analysis (MySQL)

**File:** `NEW_FILE SQL.sql`

Advanced queries performed:
- **Window Functions:** `ROW_NUMBER`, `RANK`, `DENSE_RANK`, `NTILE`, `FIRST_VALUE`
- **LAG & LEAD** for period-over-period analysis
- **CTEs** (Common Table Expressions) for complex logic
- **Subqueries** for nested filtering
- **JOINs** for multi-table analysis
- **Aggregate Functions:** Sales by region, category, segment
- **String, Date & Conditional Functions**

---

## 📈 Phase 3: Power BI Dashboard

**File:** `SuperstoreDashboard.pbix`

Dashboard highlights:
- 📌 **KPI Cards** — Total Sales, Total Profit, Total Orders, Avg Discount
- 📊 **Sales by Category & Sub-Category**
- 🗺️ **Region-wise Sales Map**
- 📅 **Monthly Sales Trend** (Time Series)
- 👥 **Customer Segment Analysis**
- 🚚 **Ship Mode Distribution**
- 🔽 **Interactive Slicers** — Region, Segment, Category, Year

---

## 💡 Key Insights

- 📦 **Technology** is the highest revenue-generating category
- 📉 **Furniture** has the lowest profit margins despite decent sales
- 🏆 **West region** leads in overall sales performance
- 🎯 **Consumer segment** contributes the most to total orders
- 🚀 **Standard Class** is the most used shipping mode
- 💸 High discounts on certain sub-categories are leading to negative profits

---

## 🖼️ Dashboard Preview

![Superstore Dashboard](dashboard_screenshot.png)

---

## 🚀 How to Run This Project

1. **Clone the repo:**
   ```bash
   git clone https://github.com/nitish-raj98/Customer_Data_Analysis.git
   ```

2. **Python Notebook:**
   - Open `Myworking.ipynb` in Jupyter Lab
   - Run all cells to see data cleaning steps

3. **SQL Queries:**
   - Import `Superstoredata.csv` into MySQL
   - Run `NEW_FILE SQL.sql` in MySQL Workbench

4. **Power BI Dashboard:**
   - Open `SuperstoreDashboard.pbix` in Power BI Desktop
   - Connect to your MySQL database if needed

---

## 👨‍💻 About Me

**Nitish Raj**
Senior Data Analyst | New Delhi, India

💼 Skills: Python • SQL • Power BI • Advanced Excel • Machine Learning
📫 Connect with me on [LinkedIn](https://linkedin.com/in/nitish-raj-63b82b262)
🐙 More projects: [GitHub](https://github.com/nitish-raj98)

---

⭐ *If you found this project helpful, please consider giving it a star!*
