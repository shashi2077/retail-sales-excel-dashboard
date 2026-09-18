# Analysis Notes

## Portfolio dataset summary

- Transactions: **600**
- Total Revenue: **₹1,06,70,943**
- Total Profit: **₹37,00,014**
- Profit Margin: **34.7%**
- Highest-revenue region: **North**
- Highest-revenue category: **Furniture**
- Highest-revenue month: **2025-11**

## Questions answered

1. Which region contributes the most revenue?
2. Which product categories generate the most revenue?
3. How do monthly revenue and profit trend?
4. What is the overall profit margin?
5. Which dimensions should management monitor regularly?

## Excel practice formulas

```excel
=H2*I2*(1-J2)
=H2*K2
=M2-N2
=SUMIF($C:$C,A2,$M:$M)
=COUNTIF($C:$C,A2)
=IFERROR(Profit/Revenue,0)
```

## Business interpretation

The dashboard is designed for management review rather than row-by-row inspection. KPI cards give an immediate business snapshot, while region/category/month views help identify where performance is concentrated and where deeper investigation may be useful.
