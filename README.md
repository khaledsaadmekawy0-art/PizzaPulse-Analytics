<img width="1823" height="587" alt="Screenshot 2026-07-31 122402" src="https://github.com/user-attachments/assets/a6a45adc-b357-42ff-9160-afaad956d3f2" />
# PizzaPulse-Analytics
# 🍕 Pizza Sales Analysis & Dashboard

An end-to-end data analysis project exploring pizza restaurant sales performance, customer ordering trends, revenue distribution, and product popularity.

---

## 📌 Project Overview

This repository contains data and analysis on pizza orders, customer purchasing behavior, and overall revenue performance. The primary goal is to extract actionable business insights regarding menu optimization, peak sales hours, popular categories, and revenue drivers.

## 📊 Dataset Summary

The dataset (`sales pizza.xlsx`) includes **499 transaction records** with details on:

* **Order Info:** `order_id`, `order_date`, `order_time`
* **Customer Info:** `Customer Name`
* **Product Details:** `pizza_name`, `pizza_category` (Classic, Veggie, Supreme, Chicken), `pizza_size` (S, M, L, XL, XXL), `pizza_ingredients`
* **Financials:** `quantity`, `unit_price`, `Sales`

---

## 🛠️ Tech Stack & Tools

* **Excel:** Pivot tables, custom dashboard layout, and raw data storage.
* **Python (Optional Analysis):** `pandas` for data cleaning, `matplotlib` / `seaborn` for visualization.
* **Markdown:** Documentation.

---

## 📈 Key Insights & Features

1. **Category Breakdown:** Analysis across major pizza categories (Classic, Supreme, Chicken, Veggie).
2. **Size Distribution:** Revenue and quantity comparisons across size offerings ($S, M, L, XL, XXL$).
3. **Top Performing Pizzas:** Identification of top sellers by total sales volume and quantity.
4. **Interactive Dashboard:** Excel sheet with customized visual cards and pivot tables for rapid filtering.

---

## 📁 Repository Structure

```text
.
├── sales pizza.xlsx      # Master Excel dataset with raw data, pivot tables, and dashboards
└── README.md             # Project documentation
