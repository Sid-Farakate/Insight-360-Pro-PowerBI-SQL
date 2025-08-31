
# 🧾 Insights 360 Pro : Finance, Sales, Marketing & Supply Chain Analytics  

AnalyticTech, a data analytics solutions provider, partnered with a global computer hardware manufacturer to analyze business performance across finance, sales, marketing, supply chain, and executive domains for FY 2019–2022.

We built a robust Power BI dashboard that empowers data-driven decisions, supporting strategy, growth, and operational excellence.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)  
- [Business Problem](#-business-problem--objective)  
- [Dataset](#-dataset--data-architecture)  
- [Tools & Technologies](#️-tools--technologies)  
- [Project Structure](#project-structure)  
- [Data Cleaning & Preparation](#-data-cleaning--preparation)  
- [Dashboard Features](#-dashboard-features)  
- [Live Dashboard](#-live-dashboard)  
- [Author & Contact](#-author--contact)  

---

## 🎯 Project Overview
A rapidly growing **global computer hardware manufacturer**, faced challenges with fragmented reporting and intuition-driven decisions.

AnalyticTech implemented **advanced Power BI analytics** for the first time in the client’s organization, enabling comprehensive insights across all business functions.

**Key Achievement**: Transformed the client’s decision-making from Excel-based intuition to **data-driven insights** using Power BI and 1.8+ million transaction records.
---

## 💼 Business Problem & Objective  

### The Challenge  
A global computer hardware manufacturer, faced critical business challenges:  

- Significant losses after American market expansion  
- Limited visibility into business performance across regions  
- Fragmented decision-making based on Excel reports and intuition  
- Competitive disadvantage due to lack of advanced analytics capabilities  

### The Solution Objective  
Build a comprehensive Power BI Business Intelligence platform to:  

✅ Enable real-time performance monitoring across all business functions  
✅ Identify profit optimization opportunities and cost reduction areas  
✅ Support strategic planning with predictive insights and trend analysis  
✅ Standardize reporting processes across global operations  
✅ Empower stakeholders with self-service analytics capabilities  

---

## 📊 Dataset & Data Architecture  

### Data Sources & Volume  
- 11 comprehensive tables from multiple data systems  
- ~1.8 million transaction records spanning FY 2019-2022  
- Multi-source integration: MySQL databases, Excel files, CSV exports  

### Core Data Tables  

**Dimension Tables (Master Data):**  
- `dim_customer`: 209 customers across 27 markets with platform and channel information  
- `dim_market`: 27 markets across 7 sub-zones and multiple regions (APAC, EU, LATAM)  
- `dim_product`: 397 products across 3 divisions (P&A, PC, N&S) and 14 categories  

**Fact Tables (Transactional Data):**  
- `fact_sales_monthly`: ~1.88M records of actual sales transactions  
- `fact_forecast_monthly`: ~1.88M records for demand forecasting  

**Financial & Cost Tables:**  
- freight_cost, manufacturing_cost, gross_price  
- pre_invoice_deductions, post_invoice_deductions  
- market_share, operational_expense, ns_gm_target  

---

## 🛠️ Tools & Technologies  

### Core Technology Stack  
- **Power BI Desktop**: Primary analytics and dashboard development platform  
- **DAX (Data Analysis Expressions)**: Advanced calculations and business logic implementation  
- **Power Query**: ETL processes and data transformation  
- **MySQL**: Database management and data querying  
- **Excel**: Data processing and supplementary analysis  
- **DAX Studio**: Report optimization and performance enhancement  

### Advanced Techniques Implemented  
- Data modeling using Snowflake schema methodology  
- Dynamic measures and calculated columns  
- Interactive bookmarks and page navigation  
- Conditional formatting and KPI indicators  
- Custom tooltips and dynamic titles  
- Power BI Service publishing and collaboration features  

---

## 🔧 Data Cleaning & Preparation  

### Data Integration & ETL Process  
- **MySQL Connection:** Established secure connections to databases  
- **Excel/CSV Import:** Integrated supplementary data files using Power Query  
- **Data Validation:** Implemented quality checks removing invalid records and handling missing values  

### Data Transformation  
- **Fiscal Year Alignment:** Created custom fiscal year calendar for business reporting  
- **Calculated Columns:** Developed Net Sales, COGS, Gross Margin, and Net Profit calculations  
- **Data Modeling:** Implemented STAR schema with optimized relationships for performance  

---

## 📊 Dashboard Features  

### Multi-View Analytics Platform  

🏠 **Home View**  
- Central navigation hub providing easy access to all dashboard sections with user-friendly interface  

💰 **Finance View**  
- Comprehensive P&L statements with year-over-year comparisons  
- Net sales trends and performance breakdowns by products/customers  
- Operational expenses analysis and budget variance reporting  

📈 **Sales View**  
- Customer performance matrix with sales and profitability metrics  
- Product performance analysis with interactive filtering capabilities  
- Sales channel effectiveness and market segment analysis  

🎯 **Marketing View**  
- Market share analysis and competitive positioning insights  
- Product segment performance with gross margin variance analysis  
- Regional marketing effectiveness and ROI measurement  

📦 **Supply Chain View**  
- Forecast accuracy trends and demand planning insights  
- Inventory stock risk analysis by customers and products  
- Supply chain cost optimization and efficiency metrics  

👔 **Executive View**  
- High-level KPI dashboard for strategic decision-making  
- Revenue contribution analysis by division and channel  
- Top customers and products performance summary  
- Market share trends and competitive analysis  

---

## 🌐 Live Dashboard 
[🔗 View Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjcxYzMxMmQtZDRhMi00YzU5LThjZDItOTYzZmNhMTg0NGE4IiwidCI6ImJiNDY2NWQ2LTg4NzItNGIyMy1hY2U3LWFlZjE4YjcxYjBiZiJ9)  

---

## 👨💻 Author & Contact  

**Siddhi Farakate**  
Aspiring Data Analyst  

🎓 **Skills Demonstrated:** Power BI, DAX, SQL, Data Modeling, Business Analysis, Dashboard Design  

📧 Email: **s.faraakate@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/sidd-pharakate/)
