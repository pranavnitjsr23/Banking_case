# Banking_case

# 🏦 Banking Risk Analytics — EDA & Power BI Dashboard

An end-to-end data analytics project focused on **risk analytics in banking**, exploring how customer data can help minimize loan default risk. Includes Python-based EDA and a Power BI dashboard for business decision-making.

**Tools:** Python (Pandas, Seaborn, Matplotlib) · MySQL · Power BI | **Dataset:** Multi-table banking database

---

## 📌 Problem Statement

How can banks use customer data to decide whether to approve or reject a loan application? This project builds a foundation for that — analyzing client financial behavior to identify risk patterns.

---

## 🔍 What This Project Covers

| Phase | Details |
|---|---|
| **Database Setup** | Connected Python to a MySQL database with interlinked banking tables |
| **Data Cleaning** | Created an `Income Band` segmentation column (Low / Mid / High) |
| **EDA** | Univariate and bivariate analysis across financial and demographic variables |
| **Correlation Analysis** | Heatmap identifying key relationships between financial metrics |
| **Dashboard** | Power BI report for business stakeholders to make lending decisions |

---

## 📊 Key Insights

- **Deposits & Savings** are highly correlated — customers who deposit actively also maintain higher savings balances
- **Age & Income** show moderate correlation with savings and retirement funds, reflecting typical financial lifecycle patterns
- **Business Lending** behaves independently from personal banking metrics — serving a distinct customer segment
- **Property Ownership** is weakly correlated with banking variables, suggesting external socioeconomic factors dominate

---

## 🗂️ Dataset Overview

Five interlinked tables: `Banking Relationship`, `Client-Banking`, `Gender`, `Investment Advisor`, `Period`

Key columns include: `Age`, `Estimated Income`, `Nationality`, `Occupation`, `Risk Weighting`, `Loyalty Classification`, `Bank Loans`, `Credit Card Balance`, `Properties Owned`

---

## 📁 Files

| File | Description |
|---|---|
| `EDA.ipynb` | Python notebook — data connection, cleaning, EDA, visualizations |
| `Banking_Dashboard.pbix` | Power BI dashboard for loan decision support |

---

## 🚀 How to Run

1. Set up MySQL and import the banking database
2. Open `EDA.ipynb` and update the MySQL connection credentials
3. Run cells sequentially to reproduce the analysis
4. Open `Banking_Dashboard.pbix` in Power BI Desktop to explore the dashboard
