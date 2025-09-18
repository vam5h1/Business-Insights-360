# Business Insights 360 — Power BI Project

📊 **Enterprise-Grade Power BI Solution** integrating Finance, Sales, Marketing, Supply Chain, and Executive views into a single, interactive reporting system.  
Designed to demonstrate **end-to-end BI development**: from SQL-based data preparation to DAX-driven KPI modeling and advanced Power BI report design.

---

## 🔍 Project Overview
This project replicates a real-world **360° business intelligence system**.  
The dashboard consolidates **15+ relational tables** and **50+ DAX measures** into a unified analytical model, enabling stakeholders to monitor business health, track KPIs, and take data-driven decisions.

**Key Deliverables:**
- 🏠 **Home Page** (interactive navigation hub)
- 💰 **Finance View** (P&L metrics, margin analysis, profitability trends)
- 📦 **Sales View** (customer/product performance, contribution analysis)
- 📈 **Marketing View** (channel ROI, campaign effectiveness, spend vs revenue)
- 🚚 **Supply Chain View** (forecast accuracy, demand-supply balance, error analysis)
- 🧑‍💼 **Executive Summary** (top-level KPIs & drill-through navigation)

---

## ⚙️ Tech Stack
- **Power BI Desktop (.pbix)** for report building
- **Power Query (M)** for ETL & transformations
- **SQL (MySQL)** as the primary data source  
- **DAX (50+ measures)** for KPI logic & calculations  
- **Excel/CSV** for supplementary data sources  
- **DAX Studio** for performance tuning  

📌 *Original SQL datasets cannot be provided in this repository due to **data confidentiality agreements***. Only the `.pbix` file and view screenshots are shared.

---

## 🏗️ Data Model
- **15+ relational tables** (fact & dimension design with star schema optimization)  
- Relationships carefully managed to avoid ambiguity and circular references  
- Performance-tuned using aggregations, indexing, and query folding  

📌 Example tables:  
- Fact_Sales  
- Fact_Finance  
- Fact_SupplyChain  
- Dim_Customer  
- Dim_Product  
- Dim_Channel  
- Dim_Date  
(and more…)

---

## 📊 Example Measures (50+ created)
Some representative DAX measures include:

- **Finance:**  
  - Net Sales = `SUM(Fact_Sales[SalesAmount])`  
  - Gross Margin % = `( [Gross Margin] / [Net Sales] )`  
  - Net Profit YoY %  

- **Sales:**  
  - Customer Contribution %  
  - Top N Products (dynamic ranking)  

- **Marketing:**  
  - ROI % = `( [Marketing Revenue] - [Marketing Spend] ) / [Marketing Spend]`  
  - Channel Performance Index  

- **Supply Chain:**  
  - Forecast Accuracy %  
  - Net Error  
  - ABS Error  

- **Executive:**  
  - Consolidated Scorecard KPIs  
  - Growth vs Target Variance  

---

## 📌 Business Impact
This solution demonstrates how a **consolidated BI platform** can:  
- Provide **real-time visibility** across departments  
- Standardize KPIs for consistent decision-making  
- Enable **self-service exploration** through slicers, drill-throughs & navigation  
- Reduce reporting turnaround time from weeks to **seconds**  

---

## 📂 Repository Contents
- `Business_Insights_360.pbix` → Full Power BI dashboard  
- `screenshots/` → Screenshots of each dashboard view  

*(Optional future addition: `dax_measures.md` to document all 50+ measures for reference.)*

---

## 🚀 How to Use
1. Download/clone the repository.  
2. Open `Business_Insights_360.pbix` in Power BI Desktop.  
3. Use navigation buttons to explore Finance, Sales, Marketing, Supply Chain, and Executive dashboards.  

---

## 📈 Example Visuals
- Finance P&L waterfall chart with YoY variance  
- Sales performance by customer/product with Top N filters  
- Marketing ROI trendline by channel  
- Supply Chain forecast accuracy heatmap  
- Executive Summary dashboard with drill-through navigation  

---

## ⚠️ Data Note
The underlying SQL/Excel datasets are **not shared** in this repository due to **confidentiality agreements**.  
This project is intended to **showcase BI design, modeling, and reporting skills**, not to distribute raw business data.  

---

## 🧾 License
MIT License — feel free to reference for learning or inspiration.
