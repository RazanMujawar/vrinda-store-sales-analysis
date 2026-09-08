# Vrinda Store — Excel Sales & Operations Analysis

## 1. Project Overview

This project analyzes the 2022 Vrinda Store order dataset using Microsoft Excel to understand sales performance, customer behavior, order outcomes, product/category performance, geographic contribution and marketplace/channel performance.

The project was built as part of a Data Analyst skill-development portfolio, with a focus on strengthening:

- Advanced Excel
- Pivot Tables and Pivot Charts
- Data cleaning and transformation
- Power Query
- KPI analysis
- Business-oriented dashboarding
- Insight generation and recommendations

## 2. Business Objective

The analysis answers questions such as:

- How did monthly sales and order volume change?
- Which customer segment contributes the most revenue?
- Which product categories drive sales?
- Which sales channels are most important?
- Which states generate the most revenue?
- What proportion of orders are delivered, cancelled, returned or refunded?
- Which customer age/gender segments contribute to the business?
- Where should management focus future analysis?

## 3. Dataset

The workbook contains **31,047 transactional rows** with fields including:

- Order ID
- Customer ID
- Gender
- Age / Age Group
- Date / Month
- Order Status
- Channel
- SKU
- Category
- Size
- Quantity
- Amount
- Shipping City / State / Postal Code
- B2B indicator

### Workbook sheets

| Sheet | Purpose |
|---|---|
| `Vrinda Store Report` | Final dashboard |
| `Sales vs Orders` | Monthly sales and order trend |
| `Men vs Women` | Revenue by gender |
| `Order Status` | Delivery / cancellation / return / refund mix |
| `States` | Top states by revenue |
| `Age and Gender` | Customer mix by age group and gender |
| `Channels` | Order/channel contribution |
| `Vrinda Store` | Transaction-level source data |

## 4. KPI Snapshot

Calculated from the uploaded transaction sheet:

| KPI | Result |
|---|---:|
| Total Revenue | ₹21,176,377 |
| Unique Orders | 28,471 |
| Unique Customers | 28,437 |
| Total Quantity | 31,237 |
| Average Order Value | ₹743.79 |

> Note: The source contains 31,047 rows but 28,471 unique Order IDs, indicating that some orders contain multiple line items. Order-level KPIs therefore use distinct Order ID where appropriate.

## 5. Key Insights

### Customer mix

Women contribute approximately **64.0% of revenue**, while men contribute approximately 36.0%.

The customer base is distributed across multiple adult age groups rather than being concentrated entirely in one age band.

### Product concentration

The **Set** category generates approximately **49.6% of total revenue**.

Kurtas contribute approximately 23.4%.

Together, Sets and kurtas account for approximately **73% of revenue**, making them the most commercially important categories in the dataset.

### Channel concentration

Amazon is the largest revenue channel at approximately **35.5%**.

Myntra contributes approximately 23.3%, while Flipkart contributes approximately 21.6%.

The three largest channels together contribute approximately **81.4% of revenue**.

### Geographic concentration

Maharashtra is the largest state by revenue at approximately **₹2.99M**, followed by Karnataka and Uttar Pradesh.

### Monthly trend

March is the strongest month at approximately **₹1.93M**.

Revenue then trends downward through much of the year, reaching approximately **₹1.62M in December**.

The March-to-November decline is approximately 16.2%, which warrants deeper investigation into seasonality, channel performance, product mix, promotions and customer demand.

## 6. Business Recommendations

1. **Protect the core categories:** Monitor inventory availability, pricing and promotions for Sets and kurtas.
2. **Reduce channel dependency risk:** Track channel-level profitability, return rate and growth, not just revenue.
3. **Investigate the post-March decline:** Break the decline down by channel, category, state and customer segment.
4. **Move from revenue to profitability:** Add product cost/margin data if available.
5. **Analyze customer value:** Add repeat-purchase rate, customer lifetime value and AOV by segment.
6. **Analyze operational leakage:** Compare cancellations, returns and refunds by channel/category.

## 7. Skills Demonstrated

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Slicers
- KPI reporting
- Data cleaning
- Power Query
- Data analysis
- Customer segmentation
- Sales analysis
- Business reporting
- Insight generation

## 8. Suggested Repository Structure

```text
Vrinda-Store-Excel-Analysis/
│
├── README.md
├── Vrinda Store Data Analysis.xlsx
├── dashboard/
│   └── vrinda_store_dashboard.png
├── data/
    └── source_dataset.xlsx
```

If the original dataset is redistributed publicly, verify its licensing/usage rights before committing it to GitHub.

## 9. How to Review the Project

1. Open the workbook.
2. Start from `Vrinda Store Report`.
3. Review each supporting analysis sheet.
4. Trace dashboard KPIs back to the underlying calculations.
5. Compare the dashboard findings with the Insights section of this README.
6. Try to identify at least two additional questions that the dashboard does not currently answer.

## 10. Learning Outcome

The main learning objective was to move from:

> "I can make an Excel dashboard."

to:

> "I can use Excel to transform transactional data into KPIs, identify business patterns and communicate actionable findings."

## 11. Attribution

This project was developed while following a guided Excel analytics project/tutorial for learning purposes and then documented as part of a personal Data Analyst portfolio.

Tutorial reference used during learning:

- Excel project: https://www.youtube.com/watch?v=gTK5rNhWJyA
- Power Query learning reference: https://www.youtube.com/watch?v=FGWMJuAjEGw
