# Brazil-Ecommerce-Analysis
<!-- Banner Image -->
![Project Banner](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Banner%20Image.png)

# 🛒 Brazilian E-Commerce Data Analysis

## 📌 Project Overview

This project explores Brazil’s largest e-commerce dataset from Olist, focusing on sales trends, customer behavior, delivery patterns, and product performance. Using SQL and data visualization techniques, the analysis provides valuable insights for businesses to improve customer satisfaction and logistics.

---
## 🔗[Project Link]

🔍 [Brazil E-Commerce Analysis by Satyajeet Katkar](https://console.cloud.google.com/bigquery?sq=874334219759:8b2252cdf98d45b7a730a22ad1273999)

## 💻 Dataset Used
<a href="https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/brazilian_ecommerce_dataset.sql">📄 Dataset Used</a>

## ⚙️ Tech Stack

- :bulb:**Languages:** SQL- For Solving Queries
- :wrench:**Tools:** MySQL, BigQuery - For Schema and Running Queries
- :minidisc:**Data Source:** Olist Brazilian E-commerce Public Dataset

---

## 💼 My Skills Demonstrated

- :man_technologist: SQL querying and optimization  
- :chart_with_upwards_trend: Data cleaning and transformation  
- 📖 Joins, subqueries, CTEs, window functions  
- :bar_chart: Data analysis and pattern identification  
- 🖥️ Insightful visualizations and storytelling  
- 📔 Google BigQuery usage and GitHub project integration  

---

## 🎯 Project Goal

To perform end-to-end data analysis on a real-world e-commerce dataset and derive insights that can help stakeholders make informed decisions in areas like delivery time, freight costs, customer satisfaction, and top-selling categories.

---

## 📊 Insights & Expected Outcomes

- Discover **which product categories** are the most popular.
- Understand **delivery time trends** across Brazilian states.
- Analyze **freight charges** and their impact on customer decisions.
- Track **customer order patterns** and payment methods.
- Evaluate **seller performance** and regional demand concentration.

---

## 📚 Query Complexity Breakdown

### 🟢 Beginner Level (1–6)
### 🟡 Intermediate Level (7–14)
### 🔴 Advanced Level (15–19)

---

## ❓ Queries

## 🟢 Beginner Level (1-6)

### 1. Top 5 most common customer states.
![Top 5 Common States](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/top5_common_customer_states.png)

### 2. Count of Status of Orders.
![Count of Status](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/order_status.png)

### 3. 5 most common product categories.
![Most Common Product](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/top5_product_category_name_translation.png)

### 4. Customers who's order is shipped.
![Customers who's order is shipped](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/order_shipped.png)

### 5. Sellers from the state of São Paulo.
![sellers from the state of São Paulo ](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/sellers_from_s%C3%A3o%20paulo.png)

### 6. Count of unique customers in Dataset.
![unique customers](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/unique_customers.png)

## 🟡 Intermediate Level (7-14)

### 7. Average freight_value per seller.
![average freight_value per seller](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/Average_freight_value.png)

## 8. Top 5 products by total revenue.
![Top 5 products by total revenue](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/top5_products_by_revenue.png)

## 9. Categorize products based on their weight.
![Categorize based on their weight](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/weight_category.png)

## 10. Sellers along with the total number of orders they’ve fulfilled.
![sellers along with the total number of orders they’ve fulfilled](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/total_orders_by_seller.png)

## 11. All products and their total revenue.
![ all products and their total revenue](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/product_total_revenue.png)

## 12. ZIP code prefixes that appear in either the customers or the sellers table.
![ZIP code prefixes that appear in either the customers or the sellers table](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/zip_code_prefix.png)

## 13. Top 5 product categories that generated the highest total revenue from sales.
![Top 5 product categories that generated the highest total revenue](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/product_category_total_revenue.png)

## 14. Average product weight grouped by product category.
![average product weight grouped by product category](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/average_product_weight.png)

### 🔴 Advance Level (15-19)

## 15. Seller average freight vs overall.
![Seller average freight vs overall](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/Seller%20Avg%20freight%20vs%20overall.png)

## 16. Sellers whose total revenue is above the average seller revenue.
![sellers whose total revenue is above the average seller revenue](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/total_revenue_greather_than_average.png)

## 17. Calculate the total amount paid, and the total amount charged.Then, find the difference between them. Show only orders where there is a mismatch greater than 0.01 BRL between the amount paid and amount charged.
![Q.17](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/total%20amount%20paid%20vs%20total%20amount%20charged.png)

## 18. Calculate the total amount paid per order they participated in, and show how that payment compares to the average payment per order for that seller. Include only sellers who were involved in at least one order.
![Q.18](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/total%20amount%20paid%20per%20order%20(using%20partition%20by).png)

## 19. Find the earliest and latest payment from the orders they were part of, and the total amount received. Only include sellers with total payments greater than 1000 BRL.
![Q.19](https://github.com/jeet787/Brazil-Ecommerce-Analysis/blob/main/Project-Outputs/Earliest%20and%20latest%20payment%20and%20total%20amount.png)



> <h3>📘**Note:** All queries are executed in BigQuery</h3>

