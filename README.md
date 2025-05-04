# 📊 Credit Card Transaction & Customer Weekly Insights Dashboard

## 🎯 Objective

To develop a comprehensive, real-time credit card analytics dashboard that provides stakeholders with actionable insights into weekly performance metrics, customer trends, revenue growth, and operational efficiency. The solution empowers teams to proactively monitor and optimize credit card operations using data-driven intelligence.

---

## 🛠️ Data Engineering Workflow

The following steps outline the data ingestion and modeling process:

1. **Data Preparation**
   - Clean and organize raw `.csv` files for transaction and customer data.
   - Ensure consistency in date formats and categorical fields.

2. **SQL Database Setup**
   - Create PostgreSQL tables: `cc_detail` (transaction data) and `cust_detail` (customer data).
   - Define primary and foreign keys to enable relational queries.

3. **Data Import**
   - Load `.csv` files into respective SQL tables using the `COPY` command.
   - Validate integrity and uniqueness (e.g., ensuring no duplicate `client_num` values).

---

## 🔍 Key Insights (Week 53 Analysis)

- **Week-over-Week Trends**
  - 💰 **Revenue** rose by **28.8%** compared to the previous week.
  - 💳 **Transaction Volume**: Both transaction count and value experienced significant upticks.
  - 👥 **Customer Count** saw a positive increase, indicating growing card usage.

---

## 📈 Year-to-Date (YTD) Performance Overview

- **Total Revenue**: `$57M`
- **Interest Income**: `$8M`
- **Transaction Volume**: `$46M`
- **Customer Demographics**:
  - Male customers contributed: `$32M`
  - Female customers contributed: `$26M`

- **Card Tier Contribution**:
  - Blue & Silver cards account for **93%** of all transactions.

- **Top Performing States**:
  - Texas, New York, and California contribute **68%** of total revenue.

- **Operational Metrics**:
  - 📈 Activation Rate: **57.5%**
  - ⚠️ Delinquency Rate: **6.06%**

---

## 📌 Dashboards Created

1. **Credit Card Transaction Report**  
   Real-time visualization of weekly transaction performance, revenue analysis, and spending patterns by customer segments.

2. **Credit Card Customer Weekly Report**  
   Insights into customer activation, demographic trends, delinquency rates, and regional performance.

---

## ✅ Recommendations & Next Steps

- **Implement Real-Time Refresh** using DirectQuery or scheduled data pipelines to ensure up-to-date reporting.
- **Anomaly Detection Models** for fraud monitoring and early delinquency prediction.
- **Customer Segmentation** using clustering (e.g., K-Means) to target marketing efforts.
- **Data Normalization and Indexing** to optimize large-scale SQL queries for scalability.
- **Deploy Dashboard on Power BI Service** with role-level access for different departments (e.g., finance, marketing).

---

## 🧠 Tech Stack

- PostgreSQL (Data Storage)
- SQL (ETL & Transformation)
- Power BI (Data Visualization)
- Python (for future automation & ML integration)

---

## 📎 License

This project is for educational and analytical demonstration purposes only. Not intended for production use without anonymization and compliance review.
