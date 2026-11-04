# Global E-commerce Performance Intelligence

An interactive **Microsoft Excel dashboard** for exploring e-commerce sales and profitability across product categories, regions, payment methods, and time periods.

The project demonstrates an end-to-end Excel analysis workflow: data quality checks, analysis with PivotTables, KPI reporting, and an interactive dashboard with slicers.

## Dashboard Preview

![Global E-commerce Performance Dashboard](assets/Dashboard.png)

## Project at a Glance

| Item | Details |
|---|---|
| Tool | Microsoft Excel |
| Dataset size | 10,000 records |
| Dataset fields | 26 columns |
| Reporting | 8 KPI cards |
| Interactivity | PivotTables, PivotCharts, and slicers |
| Focus | Sales, profit, category, region, payment method, and monthly trends |

## Business Objective

The goal is to turn raw e-commerce transaction data into a clear view of business performance and help answer questions such as:

- How are revenue and profit changing over time?
- Which product categories contribute most to revenue and profit?
- How does performance vary across regions?
- Which payment methods are used most often?
- How do discounts relate to profitability?
- How does sales quantity vary by category?

## Tools and Excel Features

- Microsoft Excel
- PivotTables and PivotCharts
- Slicers for interactive filtering
- Excel formulas and KPI calculations
- Sorting, filtering, and data-quality checks
- Charts and dashboard layout

## Data Preparation

The dataset was reviewed before analysis. The documented preparation checks included:

- Checking for blank or missing values
- Checking for duplicate records
- Reviewing data formats
- Checking negative values
- Reviewing percentage and currency formats

These checks help make the analysis more consistent and easier to interpret.

## Analysis Performed

The workbook explores the following measures and dimensions:

| Analysis | Business question |
|---|---|
| Revenue by category | Which categories generate the most revenue? |
| Profit by category | Which categories contribute most to profit? |
| Revenue by region | Where are sales strongest? |
| Profit by region | How does profitability differ by region? |
| Quantity by category | Which categories sell the highest quantity? |
| Revenue by payment method | How is revenue distributed by payment method? |
| Monthly revenue | How does revenue change month to month? |
| Discount and profit | How can discounts be examined alongside profitability? |

## Dashboard Features

- **KPI cards:** A quick summary of key business measures (8 KPIs).
- **Interactive charts:** Visual comparisons across categories, regions, payment methods, and months.
- **Slicers:** Filter the dashboard to explore selected segments of the data.
- **Consolidated view:** Bring several performance perspectives together in one Excel dashboard.

## Key Takeaways

The following findings are based on the workbook's 10,000 transaction records and its PivotTable summaries:

- **Overall revenue:** 5,284,387.70 across the dataset.
- **Overall profit:** 1,437,638.31, with an average profit margin of approximately 23.65%.
- **Leading category:** Electronics generated the highest revenue (3,382,028.46) and the highest category profit (925,448.15).
- **Leading region:** The Middle East recorded the highest regional revenue (1,348,593.22) and regional profit (384,522.85).
- **Leading payment method:** PayPal contributed the highest revenue among payment methods (831,620.67).
- **Discount and shipping:** The dataset-wide average discount is approximately 17.67%, while average shipping time is approximately 11.44 days.

### Recommended Business Actions

- Track Electronics revenue and profitability while monitoring category concentration.
- Investigate the Middle East's performance drivers and compare them with other regions.
- Review PayPal's customer usage and payment experience alongside other payment methods.
- Monitor discount levels and shipping times together with profit margin.

*Note: These are descriptive findings from the workbook's current PivotTable summaries, not causal conclusions. Values are shown in the dataset's currency units. Interactive slicers can change the figures when filters are applied.*

## Project Files

| File | Description |
|---|---|
| [Excel Dashboard Workbook](excel_dashboard/Global_Ecommerce_Performance_Intelligence.xlsx) | Open the workbook to explore the KPI dashboard, PivotTables, PivotCharts, and slicers. |
| [Raw Dataset](raw_data/global_ecommerce_sales_dataset.csv) | Source transaction dataset used for the analysis. |
| [Project Documentation](documentation/Project_Documentation.docx) | Supporting project documentation. |
| [Dashboard Preview](assets/Dashboard.png) | View the dashboard screenshot directly on GitHub. |


## How to Explore

1. Open the Excel workbook.
2. Go to the dashboard sheet.
3. Review the KPI cards for the overall performance snapshot.
4. Use the slicers to filter the report.
5. Compare the charts and KPI values after each filter selection.

## Skills Demonstrated

- Data cleaning and validation
- Exploratory data analysis
- KPI reporting
- PivotTable and PivotChart analysis
- Interactive dashboard development
- Translating business questions into clear visual summaries

## Conclusion

This project demonstrates how Microsoft Excel can be used to organize transaction data, analyze business performance, and communicate findings through an interactive dashboard. It is a practical example of applying Excel analysis and reporting skills to an e-commerce use case.
