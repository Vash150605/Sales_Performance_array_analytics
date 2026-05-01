# Sales Performance Analytics Using NumPy

A comprehensive sales data analysis project demonstrating advanced **NumPy array operations** for business intelligence and performance analytics.

## 📊 Project Overview

This project analyzes **2 years** (2024–2025) of monthly sales data for **50 products** across **5 categories**. The entire analysis is performed using efficient, vectorized NumPy operations to showcase high-performance array computing in Python.

The goal is to extract key business insights such as monthly trends, quarterly performance, statistical metrics, and the financial impact of discounts — all without using slow Python loops.

## ✨ Key Features

- **Monthly Revenue Analysis** with statistical metrics (mean, median, std)
- **Quarterly Performance Evaluation** using array reshaping
- **Product-Month Revenue Matrix** creation using pivoting
- **Broadcasting** for applying uniform discounts (10%)
- **Peak Performance Identification** (best/worst months & quarters)
- Fully vectorized NumPy operations for optimal performance

## 📁 Dataset

- **File**: `sales_performance.csv`
- **Records**: 1,200 rows (50 products × 24 months)
- **Time Period**: Jan 2024 – Dec 2025
- **Columns**: `product_id`, `category`, `month`, `quantity_sold`, `price_per_unit`, `revenue`
- **Categories**: Home, Sports, Grocery, Clothing, Electronics

## 📈 Key Results

| Metric                        | Value                  |
|------------------------------|------------------------|
| **Total Revenue**            | ₹57,208,092.09        |
| **Mean Monthly Revenue**     | ₹2,383,670.50         |
| **Median Monthly Revenue**   | ₹2,666,538.40         |
| **Highest Monthly Revenue**  | ₹3,924,646.59         |
| **Best Quarter Revenue**     | ₹10,169,913.98        |
| **Revenue after 10% Discount**| ₹51,487,282.88       |

## 🛠️ Technologies Used

- **Python 3**
- **NumPy** — Core array operations and vectorized computations
- **pandas** — Data loading and initial exploration
- **Jupyter Notebook**
