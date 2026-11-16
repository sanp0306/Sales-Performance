# Retail Sales Performance & Customer Insights Analysis (MS Excel)

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-EDA_%26_KPI_Reporting-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

## Project Overview
An end-to-end retail sales analysis and interactive reporting project built in **Microsoft Excel** on a **25,000-row** e-commerce retail dataset. The workbook demonstrates raw data cleaning, feature engineering, dynamic formula modeling (`SUMIFS`, `COUNTIFS`, `IFERROR`), conditional formatting, and executive KPI visualization to support marketing, inventory, and regional fulfillment decisions.

---

## Repository Structure
```text
Retail-Sales-Performance-Analysis-Excel/
├── data/
│   ├── raw_retail_sales_2025.csv         # Raw dataset with duplicate entries (25,015 rows)
│   └── cleaned_retail_sales_2025.csv     # Cleaned & feature-engineered dataset (25,000 rows)
├── workbook/
│   └── Retail_Sales_Performance_Dashboard.xlsx  # Complete 4-tab Excel workbook with charts & formulas
├── DATA_DICTIONARY.md                    # Column definitions, data types, and business rules
└── README.md                             # Project documentation, methodology, and insights
```

---

## Workbook Architecture (`Retail_Sales_Performance_Dashboard.xlsx`)
1. **`Executive_Dashboard`**: High-level KPI cards (Total Gross Sales, Total Orders, Average Order Value, Delivery Rate, Women Sales Share), 4 embedded visual charts, and strategic recommendations.
2. **`Pivot_Analysis_Tables`**: 6 formula-driven summary tables analyzing Monthly Trends, Sales Channels, Gender Demographics, Top 10 States (with conditional color scales), Order Status, and Product Categories.
3. **`Data_Cleaning_Log`**: Structured audit trail documenting every preprocessing and validation step performed on the raw data.
4. **`Cleaned_Sales_Data`**: Full 25,000-record dataset with frozen headers, auto-filters, and dynamic row-level revenue formulas.

---

## Key Business Insights
* **Customer Demographics:** Women shoppers drove **~64%** of total gross sales, with strongest demand in *Ethnic Wear* and *Western Wear* among the **26–35** age group.
* **Geographic Performance:** **Maharashtra** led all states with **~₹2.98M** in gross sales (~16.5% share), followed by Karnataka and Uttar Pradesh.
* **Channel Contribution:** **Amazon** was the top acquisition channel (**~35%** of all orders), outperforming Flipkart (~26%) and Myntra (~22%).
* **Fulfillment Efficiency:** **92.0%** of orders were successfully delivered, while returns (4.0%) and cancellations (2.5%) occurred disproportionately on Cash-on-Delivery (COD) orders.

---

## Business Recommendations
1. **Targeted Regional Inventory:** Pre-allocate fast-moving *Ethnic Wear* and *Western Wear* stock to fulfillment hubs in Maharashtra, Karnataka, and Uttar Pradesh ahead of Q4 festive demand.
2. **Channel Marketing Optimization:** Double down on high-converting Amazon sponsored campaigns while testing bundle promotions on Myntra and Direct Website to improve margin retention.
3. **COD Return Reduction:** Introduce automated WhatsApp/IVR order confirmation and small prepaid UPI incentives to reduce Cash-on-Delivery return rates.

---

## Author
**Saniya Purwar**  
BCA Student | Data Analyst (SQL, Power BI, Python, Excel)  
- [LinkedIn](https://www.linkedin.com/in/saniya-purwar-244795351)  
- [GitHub](https://github.com/sanp0306)
