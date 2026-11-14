<div align="center">

<img src="Screenshot/Decathlon%20Retail%20Performance%20Dashboard%20Background.png" width="100%" alt="Decathlon Banner">

# DECATHLON RETAIL ANALYTICS

### Retail Sales & Profitability Intelligence

<p>
<img src="https://img.shields.io/badge/POWER%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/EXCEL-Dataset-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">
<img src="https://img.shields.io/badge/DAX-KPI%20Analytics-4479A1?style=for-the-badge">
<img src="https://img.shields.io/badge/POWER%20QUERY-ETL-5B2D90?style=for-the-badge">
</p>

**Turning Retail Data into Business Insights**

<br>

<a href="#dashboard">Dashboard</a> &nbsp; | &nbsp;
<a href="#data-model">Data Model</a> &nbsp; | &nbsp;
<a href="#dax">DAX Measures</a> &nbsp; | &nbsp;
<a href="#insights">Business Insights</a> &nbsp; | &nbsp;
<a href="#author">Author</a>

</div>

---

<a id="overview"></a>

## 📌 01. Project Overview

This project presents an interactive Decathlon Retail Sales & Profitability Dashboard developed using Microsoft Power BI.

The solution analyzes retail sales, profitability, product performance, sports categories, brands, and regional contributions.

Raw Excel datasets are transformed into meaningful business insights using Power Query, relational data modeling, DAX calculations, and interactive visualizations.

## 🎯 Business Objectives

- Analyze retail sales and profitability.
- Compare current-year and previous-year performance.
- Monitor monthly sales trends.
- Identify top-performing sports and brands.
- Evaluate product-level performance.
- Analyze regional sales contributions.
- Track key business performance indicators.

---

<a id="dashboard"></a>

## 📊 02. Power BI Dashboard

<div align="center">

### RETAIL PERFORMANCE

**Sales & Profitability Overview**

<img src="Screenshot/Dashboard.png" width="100%" alt="Decathlon Retail Dashboard">

</div>

### Key Performance Indicators

| KPI | Current Year | Previous Year |
|---|---:|---:|
| Net Sales YTD | ₹55.26M | ₹44.40M |
| Net Gross Profit YTD | ₹21.72M | ₹17.33M |
| Gross Margin YTD | 39.3% | 39.0% |
| Net Units Sold YTD | 46.19K | 38K |
| Net Orders YTD | 24.08K | 19.577K |
| Net AOV YTD | ₹2.82K | ₹2.27K |

### Dashboard Components

| Visualization | Business Purpose |
|---|---|
| Monthly Net Sales | Current vs Previous Year |
| Top 5 Sports | Category Performance |
| Product Type Performance | Sales & Gross Margin |
| Regional Sales | Geographical Contribution |
| Top 5 Brands | Brand Performance |
| Interactive Filters | Dynamic Analysis |

### Interactive Filters

- State
- Sport
- Product Tier
- Store Name
- Payment Method

---

<a id="data-model"></a>

## 🏗️ 03. Data Model Architecture

<div align="center">

### POWER BI DATA MODEL

<img src="Screenshot/Data_Model.png" width="100%" alt="Decathlon Data Model Architecture">

</div>

### Model Components

| Table | Description |
|---|---|
| Products | Product attributes and pricing |
| Sales | Central transaction fact table |
| Store | Store and geographical information |
| Date Table | Time intelligence |
| KPI Measures | Centralized DAX calculations |

### Data Modeling Highlights

- One-to-many relationships.
- Dedicated Date Table.
- Central Sales fact table.
- Product and Store dimensions.
- Single-direction filtering.
- Organized KPI Measures.

---

<a id="dax"></a>

## 🧮 04. DAX Measures Architecture

<div align="center">

### ORGANIZED DAX MEASURE STRUCTURE

<img src="Screenshot/DAX_Measures.png" width="100%" alt="DAX Measures Architecture">

</div>

DAX calculations are organized into six logical folders inside the KPI Measures table.

| Folder | Measures |
|---|---|
| 01 Sales | Net Sales, CY Sales, PY Sales, YTD, PYTD, YoY Growth |
| 02 Profit | Net Gross Profit, YTD, PYTD, YoY Growth |
| 03 Margin | Gross Margin, YTD, PYTD, YoY Comparison |
| 04 Units | Net Units Sold, YTD, PYTD, YoY Growth |
| 05 Orders | Net Orders, YTD, PYTD, YoY Growth |
| 06 AOV | Net AOV, YTD, PYTD, YoY Growth |

### DAX Concepts

- Year-to-Date (YTD)
- Previous Year-to-Date (PYTD)
- Year-over-Year (YoY)
- Sales Growth %
- Gross Margin %
- Average Order Value
- Dynamic KPI Display Measures

---

<a id="insights"></a>

## 💡 05. Business Insights

| Business Area | Key Finding |
|---|---|
| Sales | ₹55.26M Net Sales |
| Profit | ₹21.72M Gross Profit |
| Margin | 39.3% Gross Margin |
| Sports | Hiking recorded highest sales |
| Brand | Quechua recorded highest sales |
| Region | South contributed 31.69% |

### Business Value

- Improved retail performance visibility.
- Better sales and profitability monitoring.
- Product and brand performance evaluation.
- Regional performance comparison.
- Data-driven business decision support.

---

## ⚙️ 06. Project Workflow

<div align="center">

<table>
<tr>
<td align="center">📁<br><b>Excel Datasets</b></td>
<td align="center">➡️</td>
<td align="center">🔄<br><b>Power Query</b></td>
<td align="center">➡️</td>
<td align="center">🗂️<br><b>Data Modeling</b></td>
</tr>
<tr>
<td align="center">⬇️</td>
<td></td>
<td align="center">⬇️</td>
<td></td>
<td align="center">⬇️</td>
</tr>
<tr>
<td align="center">📊<br><b>Power BI Dashboard</b></td>
<td align="center">⬅️</td>
<td align="center">🧮<br><b>DAX Measures</b></td>
<td align="center">⬅️</td>
<td align="center">📈<br><b>KPI Calculations</b></td>
</tr>
</table>

</div>

---

## 🛠️ 07. Technology Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=excel&theme=light" height="55">

<br><br>

<img src="https://img.shields.io/badge/Microsoft%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/Power%20Query-5B2D90?style=for-the-badge">
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge">

</div>

---

## 📂 08. Repository Structure

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
├── Screenshot/
│   ├── Dashboard.png
│   ├── Data_Model.png
│   └── DAX_Measures.png
│
└── README.md
```

## 🚀 09. Project Outcome

Developed an interactive Power BI retail analytics solution demonstrating practical skills in:

- Data preparation and transformation.
- Relational data modeling.
- DAX calculations and time intelligence.
- KPI development.
- Interactive dashboard design.
- Retail sales and profitability analysis.

---

<a id="author"></a>

<div align="center">

## 👨‍💻 ABOUT THE DEVELOPER

# Anthony Raj

**Aspiring Data Analyst**

Power BI | SQL | Excel | Python

<a href="https://www.linkedin.com/in/anthony-raj/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin">
</a>

<a href="https://github.com/anthony-raj-analytics">
<img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github">
</a>

<br><br>

**Thanks for visiting my project!**

*Turning Data into Insights.*

</div>
