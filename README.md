# E-Commerce Customer Analysis

![Python](https://img.shields.io/badge/Python-3.10-1e3a5f?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scipy](https://img.shields.io/badge/scipy-003366?style=flat-square&logo=scipy&logoColor=white)
![matplotlib](https://img.shields.io/badge/matplotlib-11557c?style=flat-square&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-0a3d62?style=flat-square)

Exploratory data analysis and statistical testing on a multi-dataset e-commerce platform (ShopNow).

---

## Overview

This project analyses customer behaviour, spending patterns, and conversion using four interconnected datasets: customers, transactions, web sessions, and marketing campaigns.

---

## Projects

### Homework 1 — Exploratory Data Analysis (`hw_1_projectSalma.ipynb`)
- Merging and querying multiple datasets with pandas
- Segmenting customers by country, gender, and product category
- Visualising purchase value trends across years and categories
- Identifying patterns in conversion behaviour by device type

**Key finding:** Discounted purchases average $64 vs $80 for full-price — discounts are reducing revenue, not driving it.

---

### Homework 2 — Statistical Testing (`hw_2_projectSalma.ipynb`)
- Independent samples t-tests comparing customer segments
- Chi-square tests for categorical associations
- Pearson correlation analysis
- Business interpretation of every statistical result

**Key finding:** Discount usage has the only statistically significant effect on purchase value (p < 0.0001). Country, gender, device type, and acquisition channel show no significant differences.

---

## Tools & Skills
- Python (pandas, numpy, matplotlib, seaborn, scipy)
- Statistical testing: t-test, chi-square, Pearson correlation
- Data merging, groupby aggregation, segmentation
- Business-oriented insight writing

---

## Dataset

The ShopNow dataset includes:
- `customers.csv` — demographics and acquisition channel
- `transactions.csv` — purchase history and discount usage
- `web_sessions.csv` — session behaviour and conversion
- `marketing_campaigns.csv` — campaign data
