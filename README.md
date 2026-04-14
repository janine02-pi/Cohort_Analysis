# Cohort Analysis - E-commerce Customer Retention 2022

## 📋 Project Overview

This project performs a **Cohort Analysis** on an e-commerce dataset to analyze customer acquisition, retention behavior, and sustainable profitability in 2022.

### Dataset Overview
The analysis uses **4 main data files**:

- **EcomSales.csv**: Contains transaction data (orders, order date, sales, profit, etc.)
- **Customer.csv**: Customer information (CustomerID, Segment, AnnualIncome, BirthDate, etc.)
- **Product.csv**: Product details
- **Region.csv**: Regional information

**Total Scope**: Focus on customers who made their first purchase in 2022.

---

## 🎯 Project Objectives

### Requirement 1: Cohort Analysis & Retention Rate
- Identify the **Acquisition Month** (First Order Month) for each customer.
- Calculate **monthly retention rates** for all 12 cohorts in 2022.
- Visualize retention using heatmap to observe customer return behavior over time.

### Requirement 2: Segment Drill-down Analysis
- Compare retention rates between two major customer segments:
  - **Corporate**
  - **Consumer**
- Identify which segment has better long-term retention.

### Requirement 3: Sustainable Profitability by Annual Income
- Analyze which customer group by **Annual Income** level delivers the most **sustainable profit**.
- Evaluation criteria include:
  - Long-term retention (3–6–9–11 months)
  - Average profit per customer
  - Purchase frequency
  - Income trend stability (slope analysis)

---

## 📊 Key Insights

### 1. Overall Retention (2022)
- Retention rate after the first purchase is **critically low** (mostly 1–3%).
- No significant improvement in retention across the year.
- Customers tend to make only one purchase and rarely return.

### 2. Segment Comparison
- Comparison between Corporate and Consumer segments.

### 3. Sustainable Customer Group
- The most sustainable cohort by Annual Income trend is **2022-10** (strongest positive slope: +1,640).
- Late 2022 cohorts (Oct–Dec) show better income growth compared to early 2022 cohorts.
- Early-year cohorts (especially Jan–Mar) show declining income trends over time.

---

## 🛠️ Technologies & Tools

- **Python** (Pandas, NumPy, Matplotlib, Seaborn)
- **Google Colab / Jupyter Notebook**
- Data merging, pivot tables, and cohort analysis techniques

---

## 📁 Project Structure
```bash
Cohort-Analysis/
├── Cohort_Analysis.ipynb                 # Main Jupyter Notebook
├── README.md
├── data/
│   ├── EcomSales.csv
│   ├── Customer.csv
│   ├── Product.csv
│   └── Region.csv
├── visualizations/                       # Saved charts and heatmaps (optional)
└── requirements.txt                      
