# ShopNest Store Dashboard (Power BI)

A multi-page Power BI dashboard analysing sales, delivery and customer performance for **ShopNest (Nexusgoods)**, an e-commerce store. Built as a capstone project for the SkilloVilla Data Analytics programme.

**Tools:** Power BI, DAX
**Data:** ~99K orders, Sep 2016 - Oct 2018, modelled as a star schema of 8 related tables (orders, order items, payments, reviews, products, category translations, customers, sellers)

## Business questions answered (9 report pages)
1. Top 10 product categories by total sales
2. Delayed orders by category
3. Monthly delayed vs. on-time orders, with a drill-through detail page
4. Payment method analysis
5. Product rating analysis (highest and lowest rated categories)
6. State-wise sales
7. Seasonal (quarterly) sales patterns
8. Yearly revenue analysis

## Key findings
- 7.9% of orders (7,827) were delivered late, with delays peaking in February, March and November.
- The top 10 of 71 categories generate 62.4% of product sales, led by Health & Beauty, Watches & Gifts and Bed, Bath & Table.
- Sao Paulo alone contributes 37.5% of revenue; the top 5 states contribute 73.2%.
- Credit card is the dominant payment method (73.9%), followed by boleto (19.0%).
- Security & Services is the lowest-rated category (2.50) against a 4.01 average.
- Revenue grew from R$7.25M (2017, full year) to R$8.70M in just 10 months of 2018 (~20% up).

## Repository contents
| File | Description |
|------|-------------|
| `report/ShopNest_Dashboard_Report.docx` | Full write-up with dashboard visuals and insights for each question |

## Notes
- The .pbix file is not included in this repository because of its size. It is available on request.
- 2016 and 2018 are partial years in the source data, so 2017 is the only full-year baseline.
- The brief refers to the store as "ShopNest"; the data model uses the "Nexusgoods" naming. Both are the same dataset.

## Author
Thompson Liansanglun - [LinkedIn](https://linkedin.com/in/thompson-liansanglun-925008264)
