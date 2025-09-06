# US Debt Tracker (Excel 2021)

Excel project that tracks U.S. public debt, highlights **yearly % changes**, summarizes **monthly historicals via PivotTable**, and includes a **FORECAST.ETS** projection. Built for clarity—no macros.

## File
- `US_Debt_Tracker_Project.xlsx`

## Features
- **Monthly Historicals (PivotTable)** — Aggregated by calendar month (Values: *Average of Total Public Debt Outstanding*).
- **Yearly Percentage Changes** — Year-end totals and YoY% (last available date in Dec).
- **Projected Growth** — Time-series projection with `FORECAST.ETS`.
- **Ultimate Outputs** — Final answers summarized for easy consumption.

## Requirements
- Excel **2021** or **Microsoft 365** (uses dynamic arrays and ETS).

## How to Use
1. Open the workbook and start with **Ultimate Outputs** (summary).
2. Review **Monthly Historicals** (PivotTable) to see average TPDO by month.
3. Check **Yearly Percentage Changes** for year-end totals and YoY%.
4. See **Projected Growth** for ETS-based projection.

## Refresh
1. Append new rows in **Cleaned Data** (keep columns/headers).
2. Ensure dates are real Excel dates (not text).
3. Refresh the PivotTable (Data ▶ Refresh) if needed; other sheets spill automatically.

## Notes
- Monthly averages summarize levels and can mute intra-month volatility.
- `FORECAST.ETS` assumes consistent intervals; inspect results around gaps/outliers.

## License
MIT
