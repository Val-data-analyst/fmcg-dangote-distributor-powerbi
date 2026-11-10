# FMCG Dangote Distributor Sales - Owerri & Lagos Region

## Overview
25 orders | Dangote Sugar, Salt, Semovita, Indomie Noodles, Spaghetti | 5 Locations: Lagos, Enugu, Aba, PH, Owerri | SQL to Power BI

## Key Metrics
- **Total Final Sales:** ₦4,564,850 (after discount)
- **Total Profit:** ₦482,500
- **Average Profit Margin:** 10.61%
- **Top Sales Rep:** Chidi
- **Top Location:** Lagos
- **Top Product:** Dangote Sugar (35%)

## Dashboard
![FMCG Dashboard](897228791_2264341197470430_414891007...)

## Data Table (25 Orders)
![Data Table](FMCG_Table_as_Image.jpeg)

## DAX Used
- TOTAL_SALES = QUANTITY * PRICE
- FinalSales = TOTAL_SALES * (1 - DISCOUNT)
- Column name = DIVIDE(table name[PROFIT], table name[FINAL_SALES], 0)
- ProfitMargin% Measure = DIVIDE(SUM(PROFIT), SUM(FINAL_SALES), 0)

## Tech Stack
SQL → Power BI → DAX → Naira Formatting (₦) → GitHub
