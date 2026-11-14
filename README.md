<div align="center">

# DECATHLON
## Retail Sales & Profitability Analytics

**End-to-End Business Intelligence | Microsoft Power BI**

<p>
<img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/Excel-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">
<img src="https://img.shields.io/badge/DAX-KPI%20Measures-4479A1?style=for-the-badge">
<img src="https://img.shields.io/badge/Power%20Query-ETL-5B2D90?style=for-the-badge">
</p>

*Transforming Retail Data into Actionable Business Insights*

</div>

---

## 📌 Project Overview

This project focuses on analyzing Decathlon's retail sales and profitability performance using Microsoft Power BI.

An interactive business intelligence dashboard was developed to monitor sales trends, profitability, product performance, sports categories, brand performance, and regional contributions.

The solution transforms raw Excel datasets into meaningful business insights through data modeling, DAX calculations, and interactive visualizations.

## 🎯 Business Objectives

- Monitor overall retail sales and profitability.
- Compare current-year and previous-year performance.
- Analyze monthly sales trends.
- Identify top-performing sports and brands.
- Evaluate product-level sales and gross margins.
- Understand regional sales contributions.
- Track key business performance indicators.

## 🛠️ Technology Stack

<div align="center">

<img src="https://img.shields.io/badge/Microsoft%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">
<img src="https://img.shields.io/badge/DAX-4479A1?style=for-the-badge">
<img src="https://img.shields.io/badge/Power%20Query-5B2D90?style=for-the-badge">

</div>

| Technology | Application |
|---|---|
| Microsoft Excel | Raw Dataset Management |
| Power Query | Data Preparation & Transformation |
| Power BI | Dashboard Development |
| DAX | KPI Calculations & Time Intelligence |
| Data Modeling | Relationship Management |
| Data Visualization | Business Performance Reporting |

## 📂 Dataset Description

The project uses three primary Excel datasets.

| Dataset | Description |
|---|---|
| Products | Product details, brand, sport, product tier and pricing |
| Sales | Sales transactions, discounts, profit, quantity, orders and returns |
| Store | Store details, location, region and store format |

### Data Model

Implemented a relational data model connecting the sales fact table with product, store, and date dimensions.

**Model Structure:**

- Sales – Central transaction table.
- Products – Product dimension.
- Store – Store dimension.
- Date Table – Time intelligence dimension.
- KPI Measures – Dedicated DAX measure table.

The Products, Store, and Date Table dimensions connect to Sales through one-to-many relationships with single-direction filtering.

<div align="center">

### Data Model – Power BI Model View

<img src="Screenshots/Data_Model.png" width="100%" alt="Power BI Data Model">

</div>

## 🧮 DAX Measures & KPI Organization

Created a dedicated **KPI Measures** table to organize DAX calculations into six logical folders.

| Measure Folder | Key Calculations |
|---|---|
| 01 Sales | Net Sales, CY Sales, PY Sales, YTD, PYTD, YoY Growth |
| 02 Profit | Net Gross Profit, YTD, PYTD, YoY Growth |
| 03 Margin | Gross Margin, YTD, PYTD, YoY Comparison |
| 04 Units | Net Units Sold, YTD, PYTD, YoY Growth |
| 05 Orders | Net Orders, YTD, PYTD, YoY Growth |
| 06 AOV | Net AOV, YTD, PYTD, YoY Growth |

### DAX Implementation

- Year-to-Date (YTD) calculations.
- Previous Year-to-Date (PYTD) comparisons.
- Year-over-Year (YoY) growth calculations.
- Gross margin calculations.
- Average Order Value calculations.
- Dynamic KPI display measures.
- Monthly sales comparison measures.

A dedicated Date Table supports time-based analysis, while organized measure folders improve DAX management and maintainability.

<div align="center">

### DAX Measure Organization

<img src="Screenshots/DAX_Measures.png" width="90%" alt="DAX Measure Organization">

</div>

## 📊 Dashboard Preview

<div align="center">

### Retail Performance – Sales & Profitability Overview

<img src="Screenshots/Decathlon_Dashboard.png" width="100%" alt="Decathlon Retail Dashboard">

</div>

## 📈 Key Performance Indicators

| KPI | Current Year | Previous Year |
|---|---:|---:|
| Net Sales YTD | ₹55.26M | ₹44.40M |
| Net Gross Profit YTD | ₹21.72M | ₹17.33M |
| Gross Margin YTD | 39.3% | 39.0% |
| Net Units Sold YTD | 46.19K | 38K |
| Net Orders YTD | 24.08K | 19.577K |
| Net AOV YTD | ₹2.82K | ₹2.27K |

*YTD comparison through 15 September against the same period in 2025.*

## 📊 Dashboard Features

**01. Monthly Net Sales**
- Current Year vs Previous Year comparison.
- Monthly sales trend analysis.

**02. Top 5 Net Sales by Sport**
- Hiking, Badminton, Fitness, Cricket and Cycling.
- Category-wise sales comparison.

**03. Product Type Performance**
- Product-level sales and gross margin analysis.
- Sales vs profitability comparison.

**04. Regional Sales Performance**
- Regional sales contribution.
- Geographical performance analysis.

**05. Top 5 Net Sales by Brand**
- Brand-level sales performance.
- Identification of leading brands.

**06. Interactive Filters**
- State
- Sport
- Product Tier
- Store Name
- Payment Method

## 💡 Key Business Insights

- Net Sales reached ₹55.26M, representing 24.3% YoY growth.
- Net Gross Profit reached ₹21.72M, showing 25.3% growth.
- Overall Gross Margin reached 39.3%.
- Hiking recorded the highest sales among sports categories.
- Quechua was the leading brand by net sales.
- South region contributed 31.69% of total net sales.

## ⚙️ Project Workflow

<div align="center">

**Raw Excel Datasets**

⬇️

**Power Query – Data Preparation**

⬇️

**Data Modeling – Relationships & Date Table**

⬇️

**DAX – KPI & Time Intelligence Measures**

⬇️

**Power BI – Interactive Dashboard**

⬇️

**Business Insights & Performance Analysis**

</div>

## 📁 Repository Structure

```text
Decathlon-Retail-Analytics/
│
├── Dataset/
│   ├── products.xlsx
│   ├── sales.xlsx
│   └── store.xlsx
│
├── PowerBI/
│   └── Decathlon_Dashboard.pbix
│
├── Screenshots/
│   ├── Decathlon_Dashboard.png
│   ├── Data_Model.png
│   └── DAX_Measures.png
│
└── README.md
```

## 🚀 Project Outcome

Developed an end-to-end retail business intelligence solution using Power BI, transforming raw retail datasets into an interactive analytical dashboard.

The project demonstrates practical experience in:

- Data preparation and transformation.
- Relational data modeling.
- DAX measures and time intelligence.
- KPI development.
- Interactive dashboard design.
- Retail sales and profitability analysis.

---

<div align="center">

### 👨‍💻 Developed By

# Anthony Raj

**Aspiring Data Analyst | Power BI | SQL | Excel | Python**

<a href="https://www.linkedin.com/in/anthony-raj/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin">
</a>

<a href="https://github.com/anthony-raj-analytics">
<img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github">
</a>

</div>
