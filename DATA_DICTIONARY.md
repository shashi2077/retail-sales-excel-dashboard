# Data Dictionary

| Column | Description |
|---|---|
| Order_ID | Unique transaction identifier |
| Order_Date | Date of sale |
| Region | Sales region |
| City | Customer/order city |
| Category | Product category |
| Product | Product name |
| Sales_Channel | Online, Retail, or Corporate |
| Units | Quantity sold |
| Unit_Price | Selling price per unit before discount |
| Discount_Pct | Discount percentage as decimal |
| Unit_Cost | Cost per unit |
| Customer_Rating | Customer satisfaction rating |

## Derived fields used in Excel

- **Revenue** = Units × Unit Price × (1 − Discount %)
- **Cost** = Units × Unit Cost
- **Profit** = Revenue − Cost
- **Profit Margin %** = Profit ÷ Revenue
