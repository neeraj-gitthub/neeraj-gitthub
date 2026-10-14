# Telco Customer Churn Dashboard

A Power BI project package for the supplied single-page telco churn dashboard.

## Project files

- `Telco-Customer-Churn-Dashboard.pbix` - the supplied Power BI report.
- `Telco-Customer-Churn-Project-Report.pdf` - project overview, dashboard structure, visual bindings, usage instructions, and verification limits.

## Dashboard overview

The report contains one 1920 x 1080 page built around the `Telco_Churn` model entity. It includes KPI cards for Total Customers, Churned Customers, Churn Rate, and Avg Monthly Charge; charts for churn rate by Contract, Tenure Group, Internet Service, and Payment Method; and slicers for Internet Service and Contract.

## Open the dashboard

1. Install or open Microsoft Power BI Desktop.
2. Open `Telco-Customer-Churn-Dashboard.pbix`.
3. Use the Internet Service and Contract slicers to explore the report.
4. Clear slicer selections to return to the unfiltered view.

## Verification notes

The original source dataset, its provenance, row count, refresh date, full schema, and data-preparation history were not identifiable in the inspectable report definition. The names of measures used by the KPI cards are visible, but their DAX formulas and underlying values could not be independently verified. The PBIX includes a static insight text box; its numeric statements are described as existing dashboard annotations in the accompanying report and are not recalculated here.

No student identity or roll number is included because those details were not verified for this dashboard.
