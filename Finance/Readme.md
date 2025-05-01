# 📊 General Finance Dashboard 

This repository contains a **General Finance Dashboard** built with Power BI. It helps users visualize and understand income, expenses, and profit trends using clean, structured data and interactive visuals.

---

## 📁 Project Contents

| File | Description |
|------|-------------|
| `finance.csv` | The core dataset containing transaction records. |
| `Finance revenu.pbix` | Power BI report file with multiple visual dashboards. |
| `Home.png` | Overview dashboard with key financial summaries. |
| `Profit.png` | Tab displaying net profit calculations and insights. |
| `Revenue.png` | Visualizations related to income over time. |
| `Expense.png` | Monthly and categorical breakdown of expenses. |
| `Category.png` | Pie and bar charts grouped by expense categories. |
| `README.md` | This documentation file. |

---

## 🧾 Dataset: `finance.csv`

The dataset is structured with the following columns:

- **Date** – Transaction date (format: `YYYY-MM`)
- **Amount** – Value of the transaction
- **Category** – Type of transaction (e.g., Rent, Food, Salary)
- **Type** – `Income` or `Expense`

Sample:

| Date     | Amount | Category | Type    |
|----------|--------|----------|---------|
| 2022-04  | 50000  | Salary   | Income  |
| 2022-04  | 15000  | Rent     | Expense |
| 2022-04  | 2000   | Food     | Expense |

---

## 🧭 Power BI Tabs Overview

### 🏠 **Home**
A high-level dashboard showing:
- Total Income
- Total Expense
- Net Balance
- KPIs and summary cards

### 💰 **Profit**
Visualizes monthly profit (Income - Expense) over time, allowing quick insights into financial health and fluctuations.

### 📈 **Revenue**
Focuses exclusively on income sources, trends, and peak earning months.

### 💸 **Expense**
Breakdown of monthly expenses and how they change over time, using line/bar charts.

### 📊 **Category**
Category-wise analysis using pie charts and bar graphs to show how spending is distributed (e.g., Food, Utilities, Rent).



