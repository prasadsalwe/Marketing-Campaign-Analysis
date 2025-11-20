📌 Project Objective

The objective of this project is to analyze customer transactions, evaluate marketing campaign effectiveness, and understand purchasing patterns to support data-driven decision-making for XYZ Paints. The analysis helps the company identify sales growth/decline trends, customer acquisition behavior, coupon impact, and frequently bought product combinations for targeted promotions.

🗂️ Dataset Used

The project is based on six relational tables stored in a MySQL database:

sqlproject_customer – Customer demographics

sqlproject_item – Product and category information

sqlproject_customertransactiondata – Transaction-level sales data

sqlproject_couponmapping – Coupon details and discount rules

sqlproject_citydata – City, state, and tier information

sqlproject_campaign – Campaign metadata

ERD includes relationships between customers, items, transactions, coupons, cities, and campaigns.

⚙️ Process

Data Exploration — Understanding schema, keys, and cardinality across tables.

Sales Trend Analysis — Aggregating yearly/quarterly/monthly sales using SQL groupings.

Customer Acquisition Analysis — Identifying first-time users and segmenting by OrderType.

Campaign & Coupon Analysis — Comparing transactions and purchase value with vs. without coupons.

Market Basket Analysis — Self-joins to find customers buying multiple products on same day.

Sector-Wise Combination Study — Identifying popular bundles for household, industrial, and government sectors.

Insights & Interpretation — Evaluating declines, recommending promotion strategies.

📊 Key Insights

Campaign coupons significantly improved customer engagement and drove higher transaction volume.

Purchase amount from campaign coupons was substantially higher than that from normal or no coupons.

Sales showed strong growth initially (2019–2020) but a continuous decline from 2021 to 2023.

Customer acquisition also dropped sharply after 2020, especially in industrial and government sectors.

Product combinations like Item_13 & Item_16 appeared most frequently across all sectors.

Household customers displayed the most cross-product buying behavior, suggesting strong bundling potential.

🏁 Final Conclusion

The analysis highlights a clear decline in sales and customer acquisition in recent years, indicating the need for new targeted campaigns. Seasonal Push and Brand Awareness campaigns have shown the highest revenue generation and customer reach, making them suitable for future launches. Market basket analysis suggests promoting high-frequency bundles (e.g., Item_13 + Item_16) across multiple sectors to boost cross-selling. Overall, data supports revisiting campaign strategy and leveraging bundled promotions to accelerate business growth.
