# 🛒 E-Commerce Sales Analytics

### Discovering Business Insights Through Data

**MySQL | Power BI | Data Analysis**

A business-focused project exploring sales trends, profitability, customer behaviour, and order performance.

---

## 📌 Project Overview

This project analyses e-commerce order data to understand key business performance indicators. Using MySQL for querying and Power BI for visual reporting, it explores revenue, profit, product categories, customer segments, city-wise performance, payment methods, and order status.

## 🎯 Business Objectives

- Evaluate total orders, revenue, and average order value.
- Compare sales and profit across product categories.
- Identify top-performing products and cities.
- Understand customer segment performance and payment preferences.
- Examine order status and high-value transactions.

## 🧰 Tools & Technologies

| Tool | Application |
|---|---|
| **MySQL** | Data querying, aggregation, and business analysis |
| **Power BI** | Data visualisation and reporting |
| **CSV** | Dataset storage and data exchange |

## 📊 Dataset Overview

The dataset **`Ecommerce_Sales_Dataset.csv`** contains **1,000 records and 14 columns**, covering order details, products, customers, sales, costs, profit, payments, and order status.

| Column | Description |
|---|---|
| `order_id` | Order reference |
| `order_date` | Order date |
| `city` | City associated with the order |
| `customer_segment` | Customer group |
| `product` | Product name |
| `category` | Product category |
| `quantity` | Units ordered |
| `unit_price` | Price per unit |
| `discount_pct` | Discount percentage |
| `sales` | Sales amount |
| `cost` | Order cost |
| `profit` | Profit amount |
| `payment_mode` | Payment method |
| `order_status` | Order status |

## 🔍 SQL Analysis

The SQL script contains **34 business questions**, organised into five analysis areas:

1. **Business Understanding** — Total orders, revenue, unique cities, and order values.
2. **Sales Performance** — Category-wise sales, product quantities, customer segments, and city-wise sales.
3. **Profit Analysis** — Total and category-wise profit, average profit, and profitable products and cities.
4. **Customer & Order Analysis** — Customer segments, payment methods, discounts, and order conditions.
5. **Management-Level Analysis** — Top products, highest-profit orders, top cities, and order status.

**SQL concepts applied:** `SELECT`, `WHERE`, `DISTINCT`, `GROUP BY`, `HAVING`, `ORDER BY`, `LIMIT`, aggregate functions, and logical operators.

## 📈 Power BI Dashboard

The project includes a Power BI report (`.pbix`) to explore e-commerce performance through visual reporting. Open the file in **Power BI Desktop** to view the dashboard and its available visuals and interactions.

## 📁 Repository Structure

```text
E-Commerce-Sales-Analytics/
├── E_commerce_Sales_Analytics_Dashboard.pbix
├── E_commerce_SQL_Q&A.sql
├── Ecommerce_Sales_Dataset.csv
└── README.md
```

## 💡 Key Learning Outcomes

- Translated business requirements into SQL queries.
- Analysed sales, revenue, and profitability.
- Compared product, city, and customer-segment performance.
- Practised presenting business data through Power BI.

---

**Thanks for checking out this project!**

*Turning data into insights, one query at a time.*
