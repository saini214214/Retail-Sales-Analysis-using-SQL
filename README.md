# 🛍️ Retail Sales Analysis using SQL

This project showcases a comprehensive SQL-based data analysis for a retail company to improve decision-making across product management, customer segmentation, and marketing strategy.

## 📌 Overview

In the rapidly evolving retail sector, data analytics is essential to drive business decisions. This case study analyzes a company's sales, customer, and product data to uncover key insights, identify performance gaps, and recommend actions that enhance growth and customer satisfaction.

---

## 🎯 Business Goals

- Analyze product sales trends to identify high and low-performing items.
- Segment customers based on purchasing behavior for targeted marketing.
- Understand customer loyalty and repeat behavior to inform retention strategies.
- Track sales trends over time to measure growth and performance.

---

## 🧪 Data Cleaning & Preparation

Performed data preprocessing using SQL:

- ✅ Removed duplicates from `sales_transaction` table.
- ![image](https://github.com/user-attachments/assets/8c163bc6-d12b-4999-9efb-236b8f924869)

- ✅ Handled null values by replacing them with "Unknown".
- ![image](https://github.com/user-attachments/assets/ddc4c962-4810-430c-9a4b-4d01984c006e)

- ✅ Reformatted `DATE` column (stored as TEXT) to proper `DATE` type.
- ![image](https://github.com/user-attachments/assets/59ea35c1-f26e-4f78-abd1-de4c8f19896e)

- ✅ Created a clean version of tables and replaced the originals.

---

## 🧩 Problem Statements Solved

### 🛒 Product Performance Analysis
- Identify total sales and quantity sold per product.
- ![image](https://github.com/user-attachments/assets/c21d0f8d-c1bf-42f7-9a97-182d8468116e)

- Rank top 10 and bottom 10 products based on total sales revenue.
- Analyze product category performance by total sales and units sold.
- ![image](https://github.com/user-attachments/assets/a0c16261-fca3-4d57-8259-9a21de3ed58e)


### 👥 Customer Segmentation
Segmented customers based on total quantity purchased:
| Quantity Purchased | Segment       |
|--------------------|---------------|
| 0                  | No Orders     |
| 1–10               | Low           |
| 11–30              | Mid           |
| >30                | High Value    |

Counted number of customers in each segment to support targeted campaigns.
![image](https://github.com/user-attachments/assets/ec79422e-056f-4062-a6ce-0acc71c1ee4d)


### 🔁 Customer Behavior & Loyalty
- Counted number of transactions per customer.
- ![image](https://github.com/user-attachments/assets/29949e12-871a-406f-82b1-f773d39106b6)

- Identified high-frequency vs. low-frequency buyers.
- ![image](https://github.com/user-attachments/assets/c4d97730-9c35-496f-9c7f-00ddd44e7603)

- Calculated total amount spent and number of transactions per customer.
- Measured purchase duration (loyalty) by calculating days between first and last purchases.
- ![image](https://github.com/user-attachments/assets/426d3c3c-e085-41d5-a926-cd0eacaf0c4c)

- Identified repeat purchases per product-customer pair.
- ![image](https://github.com/user-attachments/assets/0e918934-96e0-424f-8338-c157fd5674b1)


### 📈 Trend & Growth Analysis
- Tracked daily sales and transactions to understand trends.
- ![image](https://github.com/user-attachments/assets/d774872f-1a5a-47ee-afe8-eee04e87edee)

- Calculated month-over-month growth rate in revenue.
- ![image](https://github.com/user-attachments/assets/d347e14a-afe1-4be7-829b-0b34b3c00e88)


---

## 🛠️ Tools Used

- **SQL** MySQL
---
