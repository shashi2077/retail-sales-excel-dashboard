# Analysis Notes

## Dataset Summary

- Transactions: **600**
- Total Revenue: **₹1,06,70,943**
- Total Profit: **₹37,00,014**
- Profit Margin: **34.7%**
- Highest-revenue region: **North**
- Highest-revenue category: **Furniture**
- Highest-revenue month: **2025-11**

## Questions Answered

1. Which region contributes the most revenue?
2. Which product categories generate the most revenue?
3. How does revenue change by month?
4. What is the overall profit margin?

## Core Excel Formulas

```excel
=H2*I2*(1-J2)
=H2*K2
=M2-N2
=SUMIF($C:$C,A2,$M:$M)
=COUNTIF($C:$C,A2)
```

## Interpretation

Region, category and monthly summaries make it easier to compare where revenue and profit are concentrated.
