# E-Commerce Inventory & Sales Data Analytics Pipeline

An end-to-end data analytics project focused on e-commerce inventory health, product variant distribution, and stockout risk mitigation using **Python**, **Pandas**, **SQL**, and **Data Visualization**.

---

## 📌 Project Overview
Efficient inventory management and variant tracking are vital for operational success in modern e-commerce architectures. This project analyzes real-world e-commerce sales and inventory data to uncover key operational metrics, evaluate SKU-level stock distribution, and identify supply-chain bottlenecks.

### Core Objectives:
- **Data Cleansing & Transformation:** Handled missing identifiers and standardized product categorical variables.
- **Exploratory Data Analysis (EDA):** Evaluated stock concentration across categories, sizing variants, and color demographics.
- **SQL Analytics Engine:** Built relational SQL queries to identify inventory distribution and flag stockout risks.
- **Supply Chain Insights:** Conducted Pareto (80/20) concentration analysis on inventory allocation.

---

## 🛠️ Tech Stack & Methodologies
- **Languages:** Python 3, SQL (SQLite)
- **Data Manipulation:** Pandas, NumPy
- **Visual Analytics:** Matplotlib, Seaborn
- **Environment:** Google Colab / Jupyter Notebook

---

## 📊 Key Insights & Analytical Findings
1. **Inventory Concentration (Pareto Principle):** 
   - The top 3 apparel categories account for over **77%** of the entire inventory stock.
   - Identified high inventory dependency on primary ethnic apparel categories (Kurta & Kurta Sets).
2. **Sizing Uniformity:** 
   - Standard apparel sizes (S, M, L, XL, XXL) maintain a consistent volume distribution across ~1,350 unique product SKUs.
3. **Operational Risk Alerts via SQL:**
   - Isolated fast-moving SKUs approaching zero inventory levels to enable automated replenishment alerts.

---

## 📂 Repository Structure
```text
├── E-Commerce Sales & Customer Segmentation Analytics.ipynb  # Complete Python & SQL Pipeline
└── README.md                                                 # Project Documentation
