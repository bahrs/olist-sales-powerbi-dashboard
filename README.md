# Olist Sales Overview — Power BI Dashboard

This project is a simple BI case based on the public **Brazilian E-Commerce Olist Dataset**.
The goal is to demonstrate basic product/sales analytics using **Python (pandas)** for data preparation and **Power BI** for dashboarding.

## Stack

- Python: pandas, Jupyter Notebook (data preparation & aggregation)
- Power BI: data model + visuals

## Data

Source: public Olist dataset from Kaggle (orders, order_items, customers).

Used tables:
- `fact_orders`: one row per order with revenue and status
- `dim_customers`: customer city and state
- `dim_date`: calendar table

## Metrics

- Total Revenue
- Total Orders
- Total Customers
- Revenue by Month
- Orders by Status
- Revenue by Customer State

## Project structure

- `notebooks/01_prepare_olist_data.ipynb` — data preparation
- `data_raw/` — raw CSV files from Kaggle
- `data_processed/` — cleaned and aggregated CSVs for BI
- `pbix/olist_sales_overview.pbix` — Power BI report file
- `img/` — dashboard screenshots
