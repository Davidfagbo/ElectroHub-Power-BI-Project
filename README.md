# ⚡ ElectroHub Sales Performance Dashboard — Power BI

<img width="1954" height="1095" alt="Screenshot (258)" src="https://github.com/user-attachments/assets/08d48457-23f1-4c83-9a13-53acab2c9c1c" />


## Project Background
ElectroHub (multi-city retail electronics company) this Power BI dashboard enables leadership to evaluate operational efficiency and make data-driven decisions that increase revenue and improve margins.

---

## Business Requirements

✔ Top & bottom 5 products by **Sales / Profit / Quantity Sold**  
✔ Sales performance tracked across **daily, monthly, quarterly & annual** trends  
✔ Relationship analysis between **Sales vs Profit**  
✔ **User-selectable** comparison between **any two time periods**  
✔ Average **discount category** performance  
✔ Total number of orders KPI  
✔ Dynamic drill-down visualizations by:  
  
  - Product  
  - Date  
  - Customer ID  
  - Promotion Category
  
✔ Sales performance comparison across multiple **cities**

---

## Key KPIs & Calculated Fields (DAX)

| Column / Metric | Description |
|----------------|-------------|
| Price Per Unit | Standardized unit pricing |
| Total Sales | Gross revenue before discount |
| Discount Percentage | Discount % applied |
| Discount Value | Dollar value of discount |
| Net Sales | Final revenue after discount |

---

## Executive Summary — Insights & Trends

<img width="1921" height="1035" alt="Screenshot (257)" src="https://github.com/user-attachments/assets/03608659-c2db-4288-84b4-47fbffbc782a" />


### Highlights
- Top products generate **most revenue AND highest profit**, confirming strong pricing strategy
- Bottom products show **high quantities sold but low margins**, driven by discounts
- Monthly sales trends highlight **seasonality**, with significant revenue spikes in promotional periods
- Certain cities contribute **high order volume but lower Net Sales** → profitability issue
- Discount analysis reveals opportunities to **reduce unnecessary markdowns**

### Recommendations
| Insight | Business Action |
|--------|----------------|
| High discount erosion on low-margin products | Introduce targeted discounting rules |
| Strong seasonal growth effects | Expand marketing during peak periods |
| Certain customer segments drive most profit | Launch loyalty-focused retention programs |
| Regional profitability imbalance | Reevaluate pricing and logistics strategies |

---

## Data Structure & Processing

✔ Data sourced from multiple sheets (`Store Data.xlsx`)  
✔ Cleaned & validated in Power BI using Power Query  
✔ Created star-schema style relationships between tables  
✔ Calculated columns + DAX measures to support business KPIs

---

## Table Visual

<img width="1857" height="1077" alt="Screenshot (259)" src="https://github.com/user-attachments/assets/96be0c34-5102-4354-aae6-5c108338b546" />


---

## Tools & Skills Used
- **Microsoft Power BI Desktop**
- Data Modeling & Star Schema Design
- DAX (Calculated Columns & Measures)
- Advanced Filtering & Slicers
- Data Cleaning & Transformation (Power Query)
- Visualization & Business Intelligence Reporting

---

## Future Enhancements
- Add forecast analytics for demand planning  
- Automated scheduled refresh with cloud data source  
- Expand customer analytics (CLV, retention performance)  


