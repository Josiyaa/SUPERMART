# Supermart Grocery Sales Dashboard

An Excel-based retail analytics dashboard built from the Supermart Grocery Sales dataset. It summarizes sales and profit performance and provides category, regional, monthly, and sub-category views.

## Project files

- `Supermart_Grocery_Sales_Dashboard.xlsx` — complete Excel workbook with dashboard, raw data, KPI summary, analysis tables, and chart data.
- `Supermart_Grocery_Sales_Dashboard.pdf` — one-page A3 landscape PDF export of the dashboard sheet.
- `Supermart_Grocery_Sales_Data.csv` — source dataset used in this project.
- `PROJECT_DOCUMENTATION.md` — project objectives, data dictionary, metrics, workbook structure, and methodology.
- `LICENSE` — MIT license for original project materials; see the dataset rights note below.
- `.gitignore` — common temporary/editor files excluded from Git.

## Dashboard highlights

- KPI cards for total sales, total profit, orders, customers, and profit margin.
- Sales by product category.
- Monthly sales trend.
- Sales and profit by region.
- Top 10 sub-categories by sales.

## Open the workbook

1. Download `Supermart_Grocery_Sales_Dashboard.xlsx`.
2. Open it in Microsoft Excel or a compatible spreadsheet application.
3. Select the **Dashboard** worksheet to view the dashboard.
4. Use the other worksheets to inspect the source data and supporting summaries.

## Key figures

The dashboard was prepared from 9,994 transaction rows. The current summary reports approximately:

| Metric | Value |
|---|---:|
| Total Sales | ₹1,49,56,982 |
| Total Profit | ₹37,47,121.20 |
| Total Orders / Records | 9,994 |
| Total Customers | 50 |
| Overall Profit Margin | 25.05% |

These figures are presented as calculated in the workbook; review the KPI_Summary sheet if you modify the source data.

## Repository setup / GitHub

1. Create a new repository on GitHub.
2. Place the files in this folder into your local project folder.
3. Open a terminal in that folder and run:

   ```bash
   git init
   git add README.md PROJECT_DOCUMENTATION.md LICENSE .gitignore Supermart_Grocery_Sales_Dashboard.xlsx Supermart_Grocery_Sales_Dashboard.pdf Supermart_Grocery_Sales_Data.csv
   git commit -m "Add Supermart grocery sales dashboard project"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

   Replace the example repository URL with your own GitHub repository URL.

## Dataset rights and privacy

The dataset is included for project reproducibility. Its original license/redistribution terms were not verified as part of this project. Before making the repository public, confirm that you have permission to redistribute the dataset; otherwise, remove the CSV and document where authorized users can obtain it. Do not upload private or confidential data.

## Notes

The workbook contains prepared analysis tables and standard Excel charts. It does not currently provide slicers or interactive PivotCharts. The PDF is a static snapshot of the dashboard sheet; changes to the workbook will not automatically update the PDF.
