# Diwali Retail Sales Analysis (Excel & Power BI)

## 📌 Project Overview
This project presents an end-to-end commercial sales analysis of retail performance during the Diwali festive season. The analysis focuses on understanding buyer demographics, high-velocity product categories, geographic demand clusters, and order unit economics using **Microsoft Excel** and **Microsoft Power BI**.

The repository provides clean data pipelines, dynamic Excel financial modeling, pivot tables, cross-sheet comparative benchmarks, and executive dashboards.

---

## 🛠️ Tools & Technologies Used
- **Microsoft Excel**: Master raw data repository, data validation & hygiene, multi-tab comparative modeling, automated Pivot Tables, dynamic formulas (`SUM`, `INDEX-MATCH`, `XLOOKUP`), conditional formatting, and executive summary charts.
- **Microsoft Power BI Desktop**: Interactive data modeling (`.pbix`), DAX metrics, KPI scorecards, visual decomposition trees, and geographic zone analysis.

---

## 📂 Repository Structure & Files
| File Name | Format | Description |
| :--- | :--- | :--- |
| `Diwali_Sales_Master_Analysis.xlsx` | `.xlsx` | Comprehensive multi-tab workbook with Master Raw Data, Cleaned Data, Pivot Aggregations, Cross-Sheet Comparisons, and an Executive Dashboard. |
| `data_analyst_project_powerbi.pbix` | `.pbix` | Interactive Power BI report file with visual dashboards, filters, slicers, and relationship models. |
| `Diwali Sales Data_DA.xlsx` | `.xlsx` | Original raw dataset file. |
| `README.md` | `.md` | Documentation explaining architecture, methodology, business insights, and KPIs. |

---

## 📊 Excel Architecture (`Diwali_Sales_Master_Analysis.xlsx`)
The primary Excel workbook is organized into five structured worksheets:

1. **`Executive_Dashboard`**:
   - Executive KPI cards: Total Revenue (₹10.6 Cr), Total Orders (28,008), Unique Transactions (11,251), and Average Order Value (AOV: ₹3,792).
   - Embedded dynamic Excel charts:
     - *Sales by Product Category (Col Chart)*
     - *Revenue by Age Group & Gender (Clustered Col Chart)*
     - *Top 6 Revenue Generating States (Bar Chart)*
     - *Geographic Zone Contribution % (Pie Chart)*
2. **`Pivot_Summary`**:
   - Aggregated business tables with automated grand totals:
     - Table 1: Gender-Wise Sales & Average Ticket Sizes
     - Table 2: Age Group Performance & Revenue Share %
     - Table 3: State-Wise Revenue & Order Volume Rankings
     - Table 4: Product Category Performance & Margin Breakdowns
3. **`Comparative_Analysis`**:
   - Cross-sheet comparative modeling:
     - *Comparison 1: Gender vs. Age Group Matrix* (analyzing female vs. male purchasing split across age brackets)
     - *Comparison 2: Marital Status & Gender Cross-Tabulation* (evaluating ticket size differences between married vs. unmarried cohorts)
     - *Comparison 3: Zone-Wise Geographic Penetration* (benchmarking Central, Southern, Western, Northern, and Eastern zones)
4. **`Cleaned_Data`**:
   - Sanitized transactional records with null values handled, data types standardized, and derived columns added (`Marital_Desc`).
5. **`Master_Raw_Data`**:
   - Original 11,251 row transactional log preserved for auditing and data lineage.

---

## 📈 Key Business Insights & Findings

1. **High Female Customer Dominance**:
   - Female consumers drove **~70% of total revenue** (₹7.43 Cr across 7,842 transactions) compared to male consumers (₹3.19 Cr across 3,409 transactions).
2. **Core Revenue Engine (Age 26–35)**:
   - Customers aged **26–35 years** formed the largest revenue contributor, generating over **₹4.26 Cr (40.2% share)**.
3. **Geographic Clustering**:
   - **Top 3 States**: Uttar Pradesh (₹1.94 Cr), Maharashtra (₹1.44 Cr), and Karnataka (₹1.35 Cr) jointly contributed over **44.5% of total sales**.
   - By zone, the **Central and Southern zones** led national retail movement.
4. **Category Drivers**:
   - **Food** (₹3.39 Cr) and **Clothing & Apparel** (₹1.65 Cr) generated the highest gross value and volume, followed by **Electronics & Gadgets** (₹1.56 Cr).

---

## 🚀 How to Open and Use
1. **Excel Workbook**:
   - Open `Diwali_Sales_Master_Analysis.xlsx` in Microsoft Excel (2016 or newer / Microsoft 365).
   - Navigate to the `Executive_Dashboard` tab for high-level numbers, or inspect `Comparative_Analysis` and `Pivot_Summary` for formulas.
2. **Power BI Dashboard**:
   - Open `data_analyst_project_powerbi.pbix` in Power BI Desktop.
   - Interact with slicers (Gender, Zone, Age Group, Product Category) to filter the report dynamically.

---

## 👤 Author
**Sagar Kale**  
*Data Operations & MIS Specialist*
