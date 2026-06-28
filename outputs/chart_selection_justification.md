\# Chart Selection Justification



\## 1. Monthly Sales Trend



\### Business Question

How have sales changed over time?



\### Why This Chart?

A line chart is the most appropriate choice because it clearly displays trends and patterns across time, making it easy to identify periods of growth, decline, or seasonal variation.



\### Fields Used

\- \*\*Columns:\*\* Order Date (Month)

\- \*\*Rows:\*\* Sales

\- \*\*Color:\*\* Blue for consistency with sales-related metrics.

\- \*\*Filters:\*\* Region, Category, Customer Segment, Ship Mode, Order Date.



\### Design Principle Applied

A simple line chart was used to highlight trends without unnecessary visual elements, allowing users to focus on changes in sales over time.



\### Mistake Avoided

A bar chart was avoided because it makes long-term trends more difficult to interpret.



\---



\## 2. Regional Sales \& Profit Performance



\### Business Question

Which regions contribute the most to sales and profit?



\### Why This Chart?

A horizontal bar chart makes it easy to compare regional performance and quickly identify high and low-performing areas.



\### Fields Used

\- \*\*Rows:\*\* Region/State

\- \*\*Columns:\*\* Sales

\- \*\*Color:\*\* Profit

\- \*\*Label:\*\* Sales values



\### Design Principle Applied

Bars were sorted to improve readability and make comparisons straightforward.



\### Mistake Avoided

Unsorted categories were avoided because they make comparisons less intuitive.



\---



\## 3. Category \& Sub-Category Profitability



\### Business Question

Which product categories and sub-categories generate the highest profit?



\### Why This Chart?

A bar chart allows direct comparison of profitability across multiple categories while clearly highlighting differences in performance.



\### Fields Used

\- \*\*Rows:\*\* Category and Sub-Category

\- \*\*Columns:\*\* Profit

\- \*\*Color:\*\* Profit

\- \*\*Label:\*\* Profit values



\### Design Principle Applied

Consistent colours and clear labels improve interpretation while reducing visual clutter.



\### Mistake Avoided

Pie charts were avoided because they are ineffective when comparing many categories.



\---



\## 4. Customer Segment Performance



\### Business Question

How do different customer segments contribute to sales?



\### Why This Chart?

A horizontal bar chart provides a simple comparison of sales across customer segments.



\### Fields Used

\- \*\*Rows:\*\* Customer Segment

\- \*\*Columns:\*\* Sales

\- \*\*Color:\*\* Profit

\- \*\*Label:\*\* Sales values



\### Design Principle Applied

Bars were sorted to emphasise the highest-performing customer segments.



\### Mistake Avoided

Complex visualisations were avoided since only a few categories needed comparison.



\---



\## 5. Shipping Performance



\### Business Question

Which shipping modes have the longest average delivery time?



\### Why This Chart?

A bar chart clearly compares average delivery days across different shipping methods.



\### Fields Used

\- \*\*Rows:\*\* Ship Mode

\- \*\*Columns:\*\* Average Delivery Days

\- \*\*Color:\*\* Shipping Delay Bucket

\- \*\*Label:\*\* Average Delivery Days



\### Design Principle Applied

Colour was used to distinguish delivery delay categories while keeping the chart easy to understand.



\### Mistake Avoided

Using total delivery days was avoided because average delivery time provides a more meaningful comparison.



\---



\## 6. Discount vs Profit Analysis



\### Business Question

How does discount affect profitability?



\### Why This Chart?

A scatter plot is the most appropriate chart because it displays the relationship between two numerical variables and highlights patterns, clusters, and outliers.



\### Fields Used

\- \*\*Columns:\*\* Discount

\- \*\*Rows:\*\* Profit

\- \*\*Color:\*\* Category

\- \*\*Size:\*\* Sales

\- \*\*Detail:\*\* Order ID



\### Design Principle Applied

Different colours separate product categories while point size adds additional business context without overcrowding the chart.



\### Mistake Avoided

A line chart was avoided because discount and profit do not represent a time-based relationship.



\---



\## 7. Return Analysis



\### Business Question

Which customer segments experience the highest number of returned orders?



\### Why This Chart?

A bar chart allows quick comparison of return counts across customer segments.



\### Fields Used

\- \*\*Rows:\*\* Customer Segment

\- \*\*Columns:\*\* Sum of Return Flag

\- \*\*Color:\*\* Customer Segment

\- \*\*Label:\*\* Number of returned orders



\### Design Principle Applied

The chart uses consistent colours and direct labels to make comparisons easy.



\### Mistake Avoided

A pie chart was avoided because it would make small differences between customer segments harder to interpret.



\---



\# Overall Dashboard Design



The dashboard was designed following common data visualisation principles. A clear hierarchy was established by placing KPI cards at the top, followed by trend analysis, regional and customer comparisons, operational performance, and return analysis. Interactive filters and dashboard actions allow users to explore the data without overcrowding the dashboard. Consistent colours, readable labels, and appropriate chart selection help communicate business insights clearly while supporting executive decision-making.

