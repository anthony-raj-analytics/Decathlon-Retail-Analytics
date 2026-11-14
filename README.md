<div align="center">

# 🏃 DECATHLON RETAIL ANALYTICS

### Retail Performance | Sales & Profitability Overview

<p>
<img src="https://img.shields.io/badge/POWER%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<img src="https://img.shields.io/badge/EXCEL-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" alt="DAX"/>
<img src="https://img.shields.io/badge/POWER%20QUERY-742774?style=for-the-badge" alt="Power Query"/>
</p>

**Transforming Retail Data into Actionable Business Insights**

<br>

<a href="#overview">Overview</a> •
<a href="#dashboard">Dashboard</a> •
<a href="#model">Data Model</a> •
<a href="#dax">DAX Measures</a> •
<a href="#insights">Insights</a> •
<a href="#author">Developer</a>

<br><br>

</div>

---

<a id="overview"></a>

## 📌 01. Project Overview

This project presents an interactive **Decathlon Retail Performance Dashboard** developed using Microsoft Power BI.

The dashboard provides a comprehensive analysis of retail sales, gross profitability, product performance, sports categories, brand performance, and regional sales contributions.

The solution transforms raw Excel datasets into meaningful business insights using Power Query, relational data modeling, DAX calculations, and interactive visualizations.

### 🎯 Project Objectives

- Analyze retail sales and profitability.
- Compare Current Year vs Previous Year performance.
- Monitor monthly sales trends.
- Evaluate sports and product category performance.
- Identify top-performing brands.
- Analyze regional sales contributions.
- Track business KPIs and growth metrics.

---

<a id="dashboard"></a>

## 📊 02. Retail Performance Dashboard

<div align="center">

### SALES & PROFITABILITY OVERVIEW

<img src="./Screenshots/Dashboard.png" width="100%" alt="Decathlon Retail Performance Dashboard"/>

</div>

### 📈 Key Performance Indicators

| KPI | Current YTD | Previous YTD | YoY Change |
|:---|---:|---:|---:|
| Net Sales | ₹55.26M | ₹44.4M | +24.3% |
| Net Gross Profit | ₹21.72M | ₹17.33M | +25.3% |
| Gross Margin | 39.3% | 39.0% | +0.3 pp |
| Net Units Sold | 46.19K | 38K | +23.1% |
| Net Orders | 24.08K | 19.6K | +23.0% |
| Net AOV | ₹2.29K | ₹2.27K | +1.1% |

*YTD performance through 15 September compared with the same period in 2025.*

### 📊 Dashboard Visualizations

| Visualization | Description |
|:---|:---|
| Monthly Net Sales | Current Year vs Previous Year sales trends |
| Top 5 Sports | Net Sales performance by sports category |
| Product Type Performance | Net Sales vs Gross Margin YTD |
| Regional Sales | Regional contribution to total net sales |
| Top 5 Brands | Brand performance based on Net Sales YoY % |

### 🎛️ Interactive Filters

- State
- Sport
- Colour
- Promotion
- Payment Method

The dashboard also includes a Reset Filters button for restoring the default view.

---

<a id="model"></a>

## 🏗️ 03. Power BI Data Model

<div align="center">

### RELATIONAL DATA MODEL ARCHITECTURE

<img src="./Screenshots/Data_Model.png" width="100%" alt="Decathlon Power BI Data Model"/>

</div>

### Model Components

| Table | Purpose |
|:---|:---|
| Sales | Central transaction fact table |
| Products | Product details and pricing attributes |
| Store | Store information and geographical attributes |
| Date Table | Calendar dimension for time intelligence |
| KPI Measures | Centralized DAX calculations |

### Data Modeling Features

- One-to-many table relationships.
- Centralized Sales fact table.
- Product and Store dimension tables.
- Dedicated Date Table.
- Organized KPI Measures table.
- Structured relationship management.

---

<a id="dax"></a>

## 🧮 04. DAX Measures Architecture

<div align="center">

### ORGANIZED DAX MEASURE STRUCTURE

<img src="./Screenshots/DAX_Measures.png" width="100%" alt="Decathlon DAX Measures Architecture"/>

</div>

DAX measures are organized into six dedicated folders within the KPI Measures table.

### DAX Measure Categories

| Folder | Measure Categories |
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

### Key Findings

**1. Sales Performance**
- Generated ₹55.26M in Net Sales.
- Achieved 24.3% year-over-year sales growth.

**2. Profitability**
- Generated ₹21.72M Net Gross Profit.
- Maintained a 39.3% Gross Margin.

**3. Sports Performance**
- Hiking recorded the highest Net Sales at ₹12.1M.
- Badminton, Fitness, Cricket, and Cycling followed.

**4. Brand Performance**
- Nabaiji recorded the highest Net Sales YoY growth at 33.94%.
- Domyos followed with 32.50%.

**5. Regional Performance**
- South contributed the highest regional sales share at 31.69%.
- West contributed 27.03%.
- North contributed 22.44%.
- East and Central contributed the remaining share.

### Business Value

- Improved retail performance visibility.
- Better sales and profitability monitoring.
- Identification of high-performing sports and brands.
- Regional performance comparison.
- Data-driven business decision support.

---

## ⚙️ 06. Project Workflow

<div align="center">

| Stage | Process |
|:---:|:---|
| 01 | 📁 Excel Dataset Collection |
| 02 | 🔄 Power Query Transformation |
| 03 | 🏗️ Relational Data Modeling |
| 04 | 🧮 DAX Measure Development |
| 05 | 📊 Interactive Dashboard Development |
| 06 | 💡 Business Insights & Reporting |

</div>

---

## 🛠️ 07. Technologies & Tools

<div align="center">

<table>
<tr>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<br><br>
<b>Microsoft Power BI</b>
<br>
<sub>Dashboard Development & Visualization</sub>
</td>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Microsoft Excel"/>
<br><br>
<b>Microsoft Excel</b>
<br>
<sub>Dataset Management</sub>
</td>
</tr>
<tr>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/Power%20Query-742774?style=for-the-badge" alt="Power Query"/>
<br><br>
<b>Power Query</b>
<br>
<sub>Data Cleaning & Transformation</sub>
</td>
<td align="center" width="50%">
<img src="https://img.shields.io/badge/DAX-0078D4?style=for-the-badge" alt="DAX"/>
<br><br>
<b>DAX</b>
<br>
<sub>KPI Calculations & Time Intelligence</sub>
</td>
</tr>
</table>

</div>

---

## 📂 08. Dataset Overview

The project uses three Excel datasets:

| Dataset | Description |
|:---|:---|
| products.xlsx | Product information |
| sales.xlsx | Sales transaction records |
| store.xlsx | Store and regional information |

---

## 🚀 09. Project Outcome

Developed an interactive retail business intelligence solution that transforms raw sales data into actionable business insights.

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

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>

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
