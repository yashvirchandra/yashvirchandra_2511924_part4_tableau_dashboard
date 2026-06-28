# Retail Executive Dashboard - Tableau

## Business Problem

The objective of this project was to design an executive dashboard in Tableau that enables retail leadership to monitor business performance and identify opportunities for improvement. The dashboard focuses on sales trends, profitability, regional performance, customer behavior, shipping performance, discounts, and product returns. Rather than presenting isolated charts, the goal was to build a dashboard that supports business decision-making through clear visual storytelling.

---

## Dataset Description

The project uses the provided retail sales dataset (`dashboard_sales_data.xlsx`). The dataset contains transactional sales records with information such as:

- Order Date
- Ship Date
- Region and State
- Category and Sub-Category
- Customer Segment
- Ship Mode
- Sales
- Profit
- Discount
- Quantity
- Return Flag

The data was imported into Tableau, and field types were reviewed before creating the visualizations.

---

## Tableau Workbook

The Tableau workbook (`executive_dashboard.twbx`) contains one executive dashboard supported by multiple worksheets.

The dashboard includes:

- Monthly Sales Trend
- Regional Sales & Profit Performance
- Category & Sub-Category Profitability
- Customer Segment Performance
- Shipping Mode vs Average Delivery Time
- Discount vs Profit Analysis
- Returned Orders by Customer Segment

---

## Calculated Fields

The following calculated fields were created in Tableau:

- Profit Margin
- Cost
- Average Order Value
- Return Rate
- Shipping Delay Bucket

These calculated fields were used to provide additional business metrics and improve dashboard analysis.

---

## Dashboard Components

The dashboard contains:

- 3 KPI cards
  - Total Sales
  - Total Profit
  - Profit Margin

- 7 analytical visualizations

- Interactive filters for:
  - Region
  - Category
  - Customer Segment
  - Ship Mode
  - Order Date

- Dashboard filter actions allowing one chart to update the remaining visualizations.

---

## Key Business Insights

The dashboard highlights several important business findings, including:

- Monthly sales fluctuate throughout the reporting period.
- Some regions generate higher sales than others.
- Product profitability differs significantly across categories and sub-categories.
- Customer segments contribute differently to overall sales.
- Higher discounts are not always associated with higher profits.
- Shipping methods have different average delivery times.
- Return patterns vary across customer segments.

Detailed observations are included in `outputs/business_insights.md`.

---

## Dashboard Story Summary

The dashboard was designed to provide leadership with a quick overview of business performance while allowing users to drill into specific regions, product categories, customer segments, and shipping methods through interactive filters.

The visualizations work together to identify profitable business areas, operational challenges, and potential opportunities for future improvement.

---

## Assumptions and Limitations

### Assumptions

During data inspection, the following assumptions were made:

- Date fields (`Order Date` and `Ship Date`) were correctly recognized by Tableau and used for time-based analysis.
- Delivery Days were calculated as the difference between Ship Date and Order Date.
- The `Return Flag` field uses binary values (0 = Not Returned, 1 = Returned), allowing return counts and return rate calculations.
- Sales, Profit, Discount, and Quantity values were assumed to be complete and suitable for aggregation without additional data cleaning.
- Geographic fields such as Region and State were assumed to be correctly categorized for regional analysis.

### Limitations

- The dashboard is based only on the provided dataset and does not include external business factors such as marketing campaigns, economic conditions, or competitor activity.
- The analysis is descriptive and does not include forecasting or predictive models.
- Insights depend on the accuracy and completeness of the source data provided.
---

## Screenshots Included

The repository contains the following dashboard screenshots:

- Full Executive Dashboard
- Monthly Sales Trend
- Regional Performance
- Category Profitability
- Filter Interaction Example
