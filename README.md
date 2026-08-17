# ☕ Cafe Sales Analysis Dashboard | Power BI

An interactive Power BI dashboard analyzing 10,000+ cafe transactions to uncover revenue trends, product performance, and seasonal demand patterns — built as a portfolio project to demonstrate end-to-end data analysis skills.


![Dashboard Screenshot](https://github.com/nowrinayyub9231-source/Cafe-Sales-MINI-PROJECT-/blob/main/Dashboard-overview.png)


## 🎯 Objective

To analyze cafe transaction data and answer key business questions:
- What drives overall revenue — food or beverages?
- How does sales performance vary by month, day of week, and product category?
- Which items and pricing strategies generate the most revenue?
- Are there seasonal or behavioral patterns that can inform inventory and marketing decisions?

## 📂 Dataset

Size: ~10,000 transaction records
  Fields: Transaction ID, Item, Price per Unit, Quantity, Total Spent, Payment Method, Location, Transaction Date, Product Category, Order Value Category, Month Name, Day of Week

🛠️ Tools & Skills Used

- Excel — Data cleaning, handling missing/unknown values, deriving helper columns
- Power Query — Data transformation and shaping
- Power BI — Dashboard design, DAX measures, time intelligence (YTD), interactive visuals
- DAX — Custom measures for Total Sales, Average Order Value, YTD Sales, category-level aggregations

📊 Key Insights

1. Seasonal Category Shift**
Food sales peak in January (cold weather + New Year habits), while Beverage sales peak in October (autumn seasonal drinks) — an inverse seasonal pattern worth validating across future years.

2. Premium Pricing Rewarded**
Salad and Smoothie — the highest-priced items in their respective categories (Food & Beverage) — are also the top revenue drivers, showing customers reward premium healthy options rather than avoiding them.

3. Order Volume ≠ Revenue
Friday and Monday have the highest order counts, but Thursday leads in revenue despite fewer orders — while Wednesday lags on both, suggesting spend-per-visit differences and a potential midweek promotion opportunity.

4. Revenue Leadership & Peak Months
Food drives higher total revenue than Beverage overall, with three distinct seasonal revenue peaks — June (summer footfall), October (autumn beverages), and January (New Year comfort food).

📈 Dashboard Features

- KPI cards: Total Revenue, Total Orders, Average Order Value, YTD Sales vs Target
- Sales trend analysis by month (sorted Jan–Dec) and day of week
- Product category and item-level performance (tree map, bar charts)
- Orders by location and payment method
- Drill-through/detail page for transaction-level data

🚧 Challenges Solved

- Fixed custom sort order for Month Name and Day of Week (alphabetical → chronological)
- Managed "Unknown" placeholder values across multiple columns using advanced filtering
- Built dynamic DAX measures (YTD Sales, Average by Payment Method) that respond to report filters
- Resolved cross-filtering behavior between slicers sharing the same underlying table

📌 What I Learned

This project strengthened my skills in data cleaning, DAX measure design, and — most importantly — data storytelling: moving beyond "what happened" to "why it happened" and "what to do about it," using an Observation → Context → Implication → Action framework.

---

**Author:** Nowrin | Microbiology graduate transitioning into Data Analytics
📧 Open to Health care/Clinical Analyst, and Lab Analyst roles
