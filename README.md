# 📦 BDM Capstone — Sevam Pharma LLP

> **Advancing Pharmaceutical Distribution Through Data-Driven Inventory Optimization, Demand Forecasting, and Retailer Performance Analytics**

**IIT Madras | Online BS Degree Program | BDM Capstone Project**
**Submitted by:** Abhay Sharma (Roll No: 23F3001400)

---

## 🏢 About the Organization

**Sevam Pharma LLP** is a B2B pharmaceutical distributor based in Sangli, Maharashtra. The company procures medicines primarily from Sun Pharma and supplies them to retail medical stores across its operating region. As the business expanded, it began facing serious operational challenges around inventory management, expiry risk, and retailer performance — all of which this project addresses using data analysis.

---

## 🔍 Problem Statements

| # | Problem |
|---|---------|
| 1 | Improving warehouse inventory and expiry management using historical stock and sales data |
| 2 | Analyzing reasons for poor performance of specific retail outlets |
| 3 | Identifying seasonal and regional demand patterns for better forecasting |
| 4 | Understanding causes of anomalies and inconsistencies in stock and sales data |

---

## 🛠️ Tools & Technologies

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)

---

## 📊 Analytical Techniques Used

**Inventory Management**
- ABC Analysis — revenue-based product classification
- FSN Analysis — Fast, Slow, Non-moving product classification
- Inventory Comparison Analysis — Stock vs Sales mismatch detection
- Expiry Risk Analysis — custom risk score: `Months of Stock ÷ Months to Expiry`
- Inventory Turnover Analysis — `Sales ÷ Average Inventory`

**Retailer Analytics**
- Retailer-wise Sales & Contribution Analysis
- Retailer Return Impact Analysis

**Demand & Anomaly**
- Revenue Trend Analysis
- Demand Pattern Analysis (time-based)
- Correlation Analysis
- Anomaly Detection

---

## 📈 Key Findings

- **9 products** contribute ~80% of total revenue (Pareto distribution confirmed)
- Top product **PRAMIPEX ER 0.375 TA** alone = 38.85% of revenue
- **21.5%** of inventory is at high expiry risk (risk score > 1)
- A single retailer (**Pooja Palus**) accounts for **39.2% of total revenue**
- Retailers are returning **25–35%** of supplied stock — significant realization gap
- Opening–Closing stock correlation: **0.90** — inventory barely moves month to month
- Several stock records violate: `Closing = Opening + Purchase − Sales`

---

## 🗂️ Repository Structure

```
bdm-capstone-sevam-pharma/
│
├── index.html              ← Blog / project showcase (GitHub Pages)
├── README.md               ← You are here
│
├── reports/
│   ├── Proposal.pdf
│   ├── Midterm.pdf
│   └── Final.pdf
│
├── presentation/
│   └── AbhaySharma_BDM_Capstone.pptx
│
└── code/
    └── analysis.ipynb      ← Python notebook (if sharing code)
```

> ⚠️ **Note:** Raw business data is not included in this repository out of respect for Sevam Pharma LLP's data confidentiality. Dataset available via authorized Google Drive link below.

---

## 🔗 Links

| Resource | Link |
|----------|------|
| 📂 Dataset & Python Code | [Google Drive](https://drive.google.com/drive/folders/1bJx9N-o4fXlg1Ojbqj3zNyEu55Xlmnzo?usp=sharing) |
| 🎙️ Owner Interview (Proof of Originality) | [Google Drive](https://drive.google.com/drive/folders/1xNe_Zxwu7vwWJsFfQFaIfLIiEs1xsBgm?usp=sharing) |
| 🌐 Project Blog | [Live on GitHub Pages](https://YOUR-USERNAME.github.io/bdm-capstone-sevam-pharma) |

---

## 📋 Data Overview

- **Period:** February 2025 – January 2026 (12 months)
- **Datasets per month:** 3 (Sales, Purchase, Monthly Stock Statement)
- **Total medicines analyzed:** 51
- **Total retailers tracked:** 70+
- **Source:** Primary data collected directly from Sevam Pharma LLP

---

## ⚠️ Disclaimer

All data was collected with explicit written authorization from Sevam Pharma LLP. Recommendations in this project are business-specific and intended solely for academic purposes under the IIT Madras BDM Capstone Project. IIT Madras does not endorse any findings or recommendations made herein.

---

## 👤 Author

**Abhay Sharma**
IIT Madras Online BS Degree Program
Roll Number: 23F3001400

---

*Made with 🐍 Python, ☕ coffee, and a lot of Excel sheets*
