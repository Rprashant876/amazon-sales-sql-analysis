# 🛒 Amazon Sales Data — SQL Analysis Project

![SQL](https://img.shields.io/badge/Language-SQL-blue?style=flat-square)
![Dataset](https://img.shields.io/badge/Dataset-50%2C000%20Orders-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Advanced-purple?style=flat-square)

---

## 📌 Project Overview

This project performs end-to-end SQL analysis on a real-world Amazon sales dataset containing **50,000 orders** across **2 years (2022–2023)**. The analysis covers 70+ business queries ranging from basic aggregations to advanced window functions and real-world case studies.

The goal is to extract meaningful business insights to support decisions in revenue strategy, marketing, operations, and investor reporting.

---

## 📊 Dataset Description

| Field | Description |
|---|---|
| `order_id` | Unique order identifier |
| `order_date` | Date of purchase |
| `product_id` | Unique product identifier |
| `product_category` | Category of the product |
| `price` | Original price |
| `discount_percent` | Discount applied (%) |
| `discounted_price` | Price after discount |
| `quantity_sold` | Number of units sold |
| `customer_region` | Region of the customer |
| `payment_method` | Mode of payment used |
| `rating` | Customer rating (out of 5) |
| `review_count` | Number of reviews |
| `total_revenue` | Revenue generated per order |
| `profit` | Profit earned per order |

**Quick Stats:**
- 📦 Total Orders: `50,000`
- 💰 Total Revenue: `₹3,28,66,573`
- 📈 Total Profit: `₹16,43,328`
- 🗓️ Date Range: `Jan 2022 – Dec 2023`
- 🏷️ Categories: `Books, Fashion, Sports, Beauty, Electronics, Home & Kitchen`
- 🌍 Regions: `North America, Asia, Europe, Middle East`
- 💳 Payment Methods: `UPI, Credit Card, Debit Card, Wallet, Cash on Delivery`

---

## 🔍 Analysis Breakdown

### 📗 Section 1 — Basic Level
> Foundational business queries

- Total revenue, profit, quantity, and order count
- Category-wise revenue, profit, and ratings
- Region-wise revenue, order count, and average order value
- Payment method analysis

### 📘 Section 2 — Intermediate Level
> Business intelligence queries

- Year & month-wise sales trends
- Yearly revenue growth comparison
- Discount impact analysis
- Top rated and low rated products
- High review but low rating anomaly detection
- Profit margin calculations per order

### 📙 Section 3 — Advanced Level
> Window functions & subqueries

- Second and third highest revenue/profit orders
- Top 3 products per category using `RANK()`
- Cumulative revenue and running profit totals
- Regional revenue ranking
- Category-wise % contribution to total revenue
- Orders above category average revenue

### 📕 Section 4 — Real Business Case Studies

| Case Study | Business Question |
|---|---|
| **CEO Revenue Strategy** | Which categories have high revenue but low profit? Do discounts improve sales? |
| **Marketing Campaign** | Best products for festive promotions? Which have high ratings + reviews? |
| **Operations & Inventory** | Slow-moving products? Seasonal trends? Premium low-volume items? |
| **Investor Presentation** | Yearly growth, region % share, category profit contribution, risk segments |

### 🔴 Challenge / Expert Level
- Views, Stored Procedures, Triggers
- Anomaly detection (negative profit orders)
- Single dashboard query combining all KPIs

---

## 💡 Key Business Insights

> *(To be updated after query execution)*

- 📌 **[Insight 1]** — e.g., Electronics generates highest revenue but has lowest profit margin
- 📌 **[Insight 2]** — e.g., UPI is the most frequently used payment method
- 📌 **[Insight 3]** — e.g., High discounts (>30%) do not always lead to higher quantity sold
- 📌 **[Insight 4]** — e.g., North America contributes the highest revenue share

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| MySQL / PostgreSQL | Query execution |
| SQL (DDL + DML) | Data analysis |
| Window Functions | Advanced ranking & cumulative analysis |
| Subqueries & CTEs | Complex nested logic |
| GitHub | Version control & project showcase |

---

## 📁 Project Structure

```
amazon-sales-sql-analysis/
│
├── amazon_sale_dataset.csv     # Raw dataset (50,000 records)
├── analysis.sql                # All 70+ SQL queries with comments
└── README.md                   # Project documentation (this file)
```

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/amazon-sales-sql-analysis.git
   ```

2. Import the dataset into your SQL environment:
   ```sql
   CREATE DATABASE amazon_sales;
   USE amazon_sales;
   -- Then import the CSV using your tool's import wizard or LOAD DATA INFILE
   ```

3. Open `analysis.sql` and run queries section by section.

---

## 📬 Connect With Me

- 💼 [LinkedIn](https://www.linkedin.com/in/yourprofile)
- 🐙 [GitHub](https://github.com/yourusername)

---

> ⭐ If you found this project helpful, please consider giving it a star on GitHub!
