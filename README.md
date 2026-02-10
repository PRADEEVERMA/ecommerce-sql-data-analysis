# 📊 E-Commerce Sales Analysis using SQL

## 📌 Project Title
E-Commerce Sales & Customer Analytics using SQL

---

## 📖 Project Description
This project analyzes e-commerce transactional data using SQL to derive meaningful business insights.
The goal is to understand sales trends, customer behavior, product performance, and the impact of discounts on profitability.
---

## 🎯 Objectives
- Analyze overall revenue and profit performance
- Identify top-performing products and categories
- Understand customer purchasing behavior
- Evaluate discount impact on sales and profit
- Track monthly sales trends
- Generate actionable business recommendations

---

## 🗂 Database Schema
The database consists of four normalized tables:

- **customers**  
  Stores customer details such as name, city, and signup date.

- **products**  
  Contains product information including category, cost price, and selling price.

- **orders**  
  Stores order-level details such as order date and payment mode.

- **order_items**  
  Contains item-level order details including quantity and discounts.

Primary and foreign keys are used to maintain relational integrity.

---

## 📥 Dataset Overview
- 15 customers across multiple Indian cities  
- 10 products from Electronics and Accessories categories  
- 25 orders across different months  
- 40+ order line items with various discount levels  

The dataset reflects realistic e-commerce sales behavior.

---

## 🔍 Key Business Insights

### Overall Performance
- The business shows steady revenue growth over time.
- Overall profitability remains positive, indicating a healthy cost structure.

### Sales Trend Analysis
- Monthly sales increase consistently from January to July.
- Peak sales occur during mid-year months, indicating seasonal demand.

### Product Performance
- Electronics is the most profitable category.
- High-value products such as laptops, tablets, and mobile phones drive major profits.
- Accessories generate volume but lower margins.

### Customer Behavior
- A strong base of repeat customers exists.
- Repeat customers contribute higher average order value.

### City-wise Analysis
- Metro cities generate the highest revenue.
- Tier-2 cities show stable growth and future expansion potential.

### Discount Impact
- Low discounts increase sales without major profit loss.
- High discounts increase order volume but reduce profitability.

### Payment Mode Insights
- UPI is the most preferred payment mode.
- Card and Cash payments remain significant.

### Average Order Value (AOV)
- Customers often purchase multiple items per order.
- Product bundling increases order value.

---

## 📌 Business Recommendations
- Focus on high-margin electronics products
- Implement loyalty programs for repeat customers
- Optimize discount strategy (prefer low discounts)
- Strengthen marketing in metro cities
- Bundle accessories with electronics to increase AOV

---

## 🛠 Tools & Technologies
- SQL (PostgreSQL / MySQL)
- Git & GitHub

---

## 🧠 SQL Concepts Used
- Relational Database Design
- INNER JOINs
- Aggregate Functions (SUM, COUNT, AVG)
- GROUP BY & HAVING
- CASE Statements
- Subqueries
- Business-Oriented Data Analysis

---

## 📂 Repository Structure
```
SQL-Ecommerce-Sales-Analysis
│
├── 01_schema
│ └── create_tables.sql
│
├── 02_data
│ └── insert_data.sql
│
├── 03_analysis
│ └── business_queries.sql
│
├── README.md
```
---

## 🚀 Outcome
This project demonstrates the ability to transform raw transactional data into actionable business insights using SQL.
It reflects real-world analytical thinking expected from Data Analyst professionals.
