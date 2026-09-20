# E-Commerce Performance & Operations Dashboard

End-to-end analytics project: raw e-commerce data → Python cleaning and exploration → a two-page Power BI dashboard.

The dashboard answers two questions:
1. **Performance:** How is the business doing, and where does profit come from?
2. **Operations:** What is happening behind those results (cancellations, payments, customer types)?

---

## Dashboard Preview

### Performance

<img width="1371" height="749" alt="performance" src="https://github.com/user-attachments/assets/e26b190f-db3c-41c3-8a73-d6d73fe338ac" />


### Operations
![Operations page](images/operations.png)
<img width="1352" height="744" alt="operation" src="https://github.com/user-attachments/assets/eae8bb71-53a8-4b31-b004-e2e1626677e1" />

---

## Business Questions

- What are total revenue, profit, orders, return rate and cancellation rate?
- How do revenue and profit change over time (2021-2025)?
- Which regions and marketing channels generate the most profit?
- Which sales channels have the most cancellations?
- How healthy are payments and order statuses?
- Which customer segments and types contribute most revenue and profit?

## Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $177.13M |
| Total Profit | $76.15M |
| Total Orders | 138K |
| Return Rate | 6.85% |
| Cancellation Rate | 6.08% |

## Key Insights

- **South** is the top region by profit. **Organic Search** is the top marketing channel by profit, followed by Google Ads and Direct.
- **Mobile App** has the highest revenue and profit, but also the most cancellations, followed closely by Website.
- **Loyal** customers generate almost all of the profit. **New** customers contribute very little.
- **Consumer** is the largest revenue segment, followed by Premium.
- **Credit Card** is the most-used payment method. About 75% of orders are paid, ~10% pending, ~7.5% failed and ~7% refunded.
- About 82% of orders are completed. The rest are pending, cancelled or returned.
- Revenue and profit show a repeating yearly peak (seasonality) across 2021-2025.

## Dashboard Pages

**Performance:** KPI cards, revenue & profit trend, profit by marketing channel, profit by region, and profit & revenue by sales channel. Filters: Order Date, Region, Sales Channel, Customer Segment.

**Operations:** payment status, orders by order status, orders by payment method, revenue by customer segment, profit by customer type, and cancellations by sales channel. Filters: Product Category, Customer Type, Payment Method.

## Tools Used

- **Python** (pandas, NumPy, matplotlib, seaborn): data audit, cleaning, feature engineering and exploratory charts
- **Jupyter Notebook:** analysis environment
- **Power BI Desktop:**  DAX measures, interactive dashboard
