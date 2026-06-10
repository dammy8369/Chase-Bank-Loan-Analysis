# 🏦 Chase Bank Loan Report

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

A comprehensive loan analytics dashboard built with **SQL** and **Power BI**, analysing Chase Bank's loan portfolio performance across 38,600+ applications totalling over **$435.8M** in funded loans.

---

## 📊 Dashboard Pages

### 1. Summary
![Summary Page](visuals/summary.png)

A high-level overview of the entire loan portfolio, including good vs bad loan classification and a detailed loan status breakdown table.

---

### 2. Overview
![Overview Page](visuals/overview.png)

Trend and distribution analysis across multiple dimensions — monthly performance, geographic spread, loan term, employment length, loan purpose, and home ownership.

---

### 3. Details
![Details Page](visuals/details.png)

A granular, row-level view of individual loan records with key fields including loan purpose, home ownership, grade, issue date, funded amount, interest rate, installment, and amount received.

---

## 📌 Key Metrics

| Metric | Value |
|--------|-------|
| Total Loan Applications | 38.6K |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Average Interest Rate | 12.0% |
| Average DTI | 13.3% |
| Good Loan Rate | 86.2% |
| Bad Loan Rate | 13.8% |

---

## 💡 Key Insights

- **86.2%** of all loans issued were classified as **Good Loans**, with 33K applications funded at $370.2M
- **Bad Loans** accounted for 13.8% (5.3K applications), with $65.5M funded but only $37.3M recovered
- **Fully Paid** loans dominate the portfolio at 32,145 applications, generating $411.6M in amount received
- **Debt Consolidation** is the top loan purpose, receiving $0.25bn — far ahead of all other categories
- Loan amounts received **grew consistently month-over-month**, peaking at **$58M in December**
- **62.3%** of loans were on a **36-month term** vs 37.7% on 60-month terms
- Borrowers with **10+ years of employment** received the highest loan amounts ($0.13bn)
- **Mortgage holders** received the most loans by home ownership ($238.47M), followed by Rent ($201.82M)
- The highest loan activity by state was concentrated in **California, Texas, and New York**

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|------|-------|
| **SQL** | Data extraction, transformation, and KPI calculations |
| **Power BI Desktop** | Dashboard design, data modelling, and visualisation |
| **DAX** | Custom measures (MTD, MoM, Good/Bad Loan classification) |
| **Power Query** | Data cleaning and preparation |

---

## 📁 Repository Structure

```
chase-bank-loan-report/
│
├── README.md
├── visuals/
│   ├── summary.png
│   ├── overview.png
│   └── details.png
├── queries/
│   ├── data_extraction.sql
│   ├── kpi_metrics.sql
│   └── loan_analysis.sql
└── chase_bank_loan_report.pbix
```

---

## 🔍 Dashboard Features

- **Interactive Slicers** — Filter by State, Grade, Loan Status, Purpose, and Good vs Bad Loan across all pages
- **MTD & MoM Tracking** — Month-to-date and month-over-month performance indicators on all KPI cards
- **Dynamic Measure Selector** — Overview page allows switching between different measures on trend charts
- **Drill-through Details** — Details page provides row-level loan data for deeper investigation
- **Geographic Map** — Visual breakdown of loan distribution across all US states

---

## 👤 Author

**Damilola Buhari Kolawole**  
Junior Data Analyst | SQL • Power BI • Python  
📍 Ogun State, Nigeria

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](https://github.com/)

---

*This project was built for portfolio purposes using a publicly available loan dataset.*

