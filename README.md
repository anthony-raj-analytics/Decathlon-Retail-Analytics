<div align="center">

# 🏃 DECATHLON RETAIL ANALYTICS

### RETAIL SALES & PROFITABILITY INTELLIGENCE

<p>
  <img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
  <img src="https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
  <img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" alt="DAX"/>
  <img src="https://img.shields.io/badge/POWER%20QUERY-742774?style=for-the-badge" alt="Power Query"/>
</p>

**Transforming Retail Data into Actionable Business Insights**

<br>

<a href="#overview">Overview</a> &nbsp; • &nbsp;
<a href="#dashboard">Dashboard</a> &nbsp; • &nbsp;
<a href="#model">Data Model</a> &nbsp; • &nbsp;
<a href="#dax">DAX</a> &nbsp; • &nbsp;
<a href="#insights">Insights</a> &nbsp; • &nbsp;
<a href="#author">Developer</a>

<br><br>

<img src="./Screenshots/Dashboard.png" width="100%" alt="Decathlon Retail Performance Dashboard"/>

</div>

---

<a id="overview"></a>

## 📌 01. Project Overview

This project presents an interactive **Decathlon Retail Sales & Profitability Dashboard** developed using Microsoft Power BI.

The solution analyzes retail sales, profitability, product performance, sports categories, brands, and regional contributions.

Raw Excel datasets are transformed into meaningful business insights using Power Query, relational data modeling, DAX calculations, and interactive visualizations.

### 🎯 Business Objectives

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

<img src="./Screenshots/Dashboard.png" width="100%" alt="Decathlon Power BI Dashboard"/>

</div>

### Key Performance Indicators

| KPI | Current Year | Previous Year |
|:---|---:|---:|
| Net Sales YTD | ₹55.26M | ₹44.40M |
| Net Gross Profit YTD | ₹21.72M | ₹17.33M |
| Gross Margin YTD | 39.3% | 39.0% |
| Net Units Sold YTD | 46.19K | 38K |
| Net Orders YTD | 24.08K | 19.577K |
| Net AOV YTD | ₹2.82K | ₹2.27K |

*YTD comparison through 15 September against the same period in 2025.*

### Dashboard Components

| Visualization | Business Purpose |
|:---|:---|
| Monthly Net Sales | Current vs Previous Year |
| Top 5 Sports | Category Performance |
| Product Type Performance | Sales & Gross Margin |
| Regional Sales | Geographical Contribution |
| Top 5 Brands | Brand Performance |
| Interactive Filters | Dynamic Analysis |

### Interactive Filters

`State` &nbsp; `Sport` &nbsp; `Product Tier` &nbsp; `Store Name` &nbsp; `Payment Method`

---

<a id="model"></a>

## 🏗️ 03. Power BI Data Model Architecture

The data model connects the central Sales table with Products, Store, and Date dimensions.

<div align="center">

### RELATIONAL DATA MODEL

<img src="./Screenshots/Data_Model.png" width="100%" alt="Decathlon Data Model Architecture"/>

</div>

### Model Components

| Table | Description |
|:---|:---|
| Sales | Central transaction fact table |
| Products | Product attributes and pricing |
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

DAX calculations are organized into six logical folders inside the dedicated KPI Measures table.

<div align="center">

### ORGANIZED DAX MEASURE STRUCTURE

<img src="./Screenshots/DAX_Measures.png" width="100%" alt="Decathlon DAX Measures Architecture"/>

</div>

### DAX Measure Categories

| Folder | Measures |
|:---|:---|
| 01 Sales | Net Sales, CY Sales, PY Sales, YTD, PYTD, YoY Growth |
| 02 Profit | Net Gross Profit, YTD, PYTD, YoY Growth |
| 03 Margin | Gross Margin, YTD, PYTD, YoY Comparison |
| 04 Units | Net Units Sold, YTD, PYTD, YoY Growth |
| 05 Orders | Net Orders, YTD, PYTD, YoY Growth |
| 06 AOV | Net AOV, YTD, PYTD, YoY Growth |

### Key DAX Concepts

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
|:---|:---|
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
<td align="center"><b>01</b><br>📁<br>Excel Datasets</td>
<td align="center">➜</td>
<td align="center"><b>02</b><br>🔄<br>Power Query</td>
<td align="center">➜</td>
<td align="center"><b>03</b><br>🗂️<br>Data Modeling</td>
</tr>
<tr>
<td colspan="5" align="center">⬇️</td>
</tr>
<tr>
<td align="center"><b>06</b><br>💡<br>Business Insights</td>
<td align="center">⬅</td>
<td align="center"><b>05</b><br>📊<br>Power BI Dashboard</td>
<td align="center">⬅</td>
<td align="center"><b>04</b><br>🧮<br>DAX Measures</td>
</tr>
</table>

</div>

---

## 🛠️ 07. Technologies & Tools

<div align="center">

### CORE TECHNOLOGIES

<table>
<tr>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<br><br>
<strong>Microsoft Power BI</strong>
<br>
<sub>Dashboard Development & Visualization</sub>
</td>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
<br><br>
<strong>Microsoft Excel</strong>
<br>
<sub>Dataset Management & Preparation</sub>
</td>
</tr>
</table>

### ANALYTICS COMPONENTS

<table>
<tr>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/POWER%20QUERY-742774?style=for-the-badge" alt="Power Query"/>
<br><br>
<strong>Power Query</strong>
<br>
<sub>Data Cleaning & Transformation</sub>
</td>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" alt="DAX"/>
<br><br>
<strong>DAX</strong>
<br>
<sub>KPI Calculations & Time Intelligence</sub>
</td>
</tr>
</table>

</div>

### Technical Skills

| Category | Skills |
|:---|:---|
| Data Preparation | Data Cleaning, Data Transformation |
| Data Modeling | Relationships, Date Table |
| DAX Analytics | YTD, PYTD, YoY, KPI Measures |
| Visualization | Interactive Dashboards, KPI Cards |
| Business Intelligence | Sales & Profitability Analysis |

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
├── Screenshots/
│   ├── Dashboard.png
│   ├── Data_Model.png
│   ├── DAX_Measures.png
│   └── README.md
│
└── README.md
```

---

## 🚀 09. Project Outcome

Developed an interactive retail business intelligence solution that transforms raw sales data into meaningful business insights.

### Skills Demonstrated

- Data Preparation & Transformation
- Relational Data Modeling
- DAX Calculations & Time Intelligence
- KPI Development
- Interactive Dashboard Design
- Retail Sales & Profitability Analysis

---

<a id="author"></a>

<div align="center">

## 👨‍💻 DEVELOPED BY

# Anthony Raj

**Aspiring Data Analyst**

<br>

<img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/EXCEL-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/PYTHON-3776AB?style=flat-square&logo=python&logoColor=white"/>

<br><br>

<a href="https://www.linkedin.com/in/anthony-raj/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<a href="https://github.com/anthony-raj-analytics">
<img src="https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>

<br><br>

**THANK YOU FOR VISITING MY PROJECT**

*Turning Data into Insights.*

</div>
