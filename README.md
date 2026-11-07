# AquaInsights 360° — Drinking Water Marketplace & Product Intelligence Platform

**A GYaaNa SAroVar (GYSV) Company Project**

AquaInsights 360° is an end-to-end Business Intelligence project designed to analyse a large synthetic drinking-water marketplace dataset using Python and Microsoft Power BI.

The project explores sales performance, product portfolios, brand and manufacturer performance, marketplace and seller activity, pricing, inventory, packaging, customer ratings, and simulated water-quality attributes.

## Project Overview

| Detail | Description |
|---|---|
| Project | AquaInsights 360° |
| Organisation | GYaaNa SAroVar (GYSV) |
| Domain | Business Intelligence & Data Analytics |
| Dataset size | 10,000,000 synthetic records |
| Number of columns | 55 |
| Dataset generation | Python, NumPy, Pandas |
| Reporting platform | Microsoft Power BI |
| Analysis | DAX, data modelling, interactive dashboards |
| Dataset period | 2023-01-01 to 2026-10-25 |

## Dashboard Pages

1. **AquaRevenue 360° — Executive Sales & Revenue Intelligence**
   - Revenue, units sold, sales trends and estimated profit.
   - Category and brand revenue comparisons.

2. **AquaQuality 360° — Product Portfolio & Water Quality Intelligence**
   - Product portfolio and water-type distribution.
   - Simulated pH and TDS analysis.
   - Packaging and purification-method comparisons.

3. **AquaBrand 360° — Brand & Manufacturer Performance Intelligence**
   - Brand and company revenue comparisons.
   - Estimated profitability and product ratings.
   - Premium and non-premium brand analysis.

4. **AquaMarket 360° — Marketplace & Seller Performance Intelligence**
   - Marketplace revenue and sales comparisons.
   - Seller performance and product availability.
   - Delivery and regional analysis.

5. **AquaCommerce 360° — Pricing, Inventory & Customer Insights**
   - Selling-price and discount analysis.
   - Inventory and packaging insights.
   - Customer ratings, return-rate attributes and advanced product intelligence.

## Technology Stack

- Python
- NumPy
- Pandas
- Microsoft Power BI
- Power Query
- DAX
- CSV data processing
- Git and GitHub

## Dataset Generation

The dataset generator creates 10 million records in batches of 250,000 rows. It produces 40 CSV part files and a dataset manifest.

Dataset characteristics:
- Exactly 55 columns.
- Reproducible random seed: 42.
- Unique `Row_ID` for each generated row.
- Date range from 1 January 2023 to 25 October 2026.
- Records explicitly labelled `SYNTHETIC`.

## Repository Structure

```text
01_Dataset_Generation/
02_Dataset_Documentation/
03_PowerBI_Report/
04_Dashboard_Screenshots/
05_Python_Analysis/
06_Project_Documentation/
```

## How to Use

1. Clone or download this repository.
2. Install the Python dependencies using `pip install -r 01_Dataset_Generation/requirements.txt`.
3. Run the dataset generator.
4. Import the generated CSV files into Power BI.
5. Apply the documented data model and DAX measures.
6. Explore the five interactive report pages.

## Important Data Disclaimer

This project uses synthetic, programmatically generated data for demonstration, learning, and analytics development. It does not represent verified transactions, product listings, customer reviews, inventory, regulatory approvals, or sales performance from actual companies or marketplaces.

The pH and TDS fields are simulated attributes, not laboratory test results. FSSAI and certification fields are synthetic labels and must not be interpreted as verified regulatory status.

## Organisation

**GYaaNa SAroVar (GYSV)**  
Company project — Business Intelligence & Data Analytics

## Project Status

Developed as an end-to-end analytics project. Report screenshots, the Power BI file, supporting documentation, and dataset access will be added to this repository as they are prepared for publication.

---

**AquaInsights 360° — Turning Data into Business Intelligence.**
