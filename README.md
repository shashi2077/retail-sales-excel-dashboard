# Retail Sales Analysis

![Dashboard Preview](dashboard_preview.svg)

## Project Overview

This project analyzes **600 retail sales transactions** to summarize revenue, cost, profit and sales performance across regions, product categories and months.

## Tools and Techniques

- Microsoft Excel
- Data cleaning and structuring
- Excel tables and formulas
- SUMIF / COUNTIF
- IFERROR
- Date-based analysis
- Revenue, Cost and Profit calculations
- KPI analysis
- Charts and summary reporting

## Dataset Summary

| KPI | Result |
|---|---:|
| Transactions | 600 |
| Total Revenue | ₹1,06,70,943 |
| Total Profit | ₹37,00,014 |
| Profit Margin | 34.7% |
| Highest-Revenue Region | North |
| Highest-Revenue Category | Furniture |
| Highest-Revenue Month | November 2025 |

The dataset is synthetic. No client or employer data is used.

## Repository Structure

```text
retail-sales-excel-dashboard/
├── README.md
├── ANALYSIS_NOTES.md
├── DATA_DICTIONARY.md
├── dashboard_preview.svg
└── data/
    └── retail_sales_raw.csv
```

## Analysis Workflow

1. Validate dates, product categories, regions, prices, discounts and costs.
2. Calculate Revenue, Cost, Profit and Profit Margin.
3. Summarize results by region, category and month.
4. Compare performance using KPI summaries and charts.
5. Document the main findings.

## Core Calculations

```excel
Revenue = Units * Unit Price * (1 - Discount %)
Cost = Units * Unit Cost
Profit = Revenue - Cost
Profit Margin = Profit / Revenue
```

Example formulas used in the analysis:

```excel
=H2*I2*(1-J2)
=H2*K2
=M2-N2
=SUMIF($C:$C,A2,$M:$M)
=COUNTIF($C:$C,A2)
=IFERROR(Profit/Revenue,0)
```

## Key Findings

- **North** generated the highest regional revenue in this dataset.
- **Furniture** was the highest-revenue product category.
- **November 2025** was the highest-revenue month.
- Overall profit margin was approximately **34.7%**.

## Supporting Files

- [Raw Dataset](data/retail_sales_raw.csv)
- [Data Dictionary](DATA_DICTIONARY.md)
- [Analysis Notes](ANALYSIS_NOTES.md)

## Note

The repository contains the raw dataset, documented calculations, analysis notes and a dashboard preview.
