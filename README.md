# E-Commerce Sales Analysis

## Project Overview
This project analyzes the Brazilian E-Commerce Public Dataset to understand sales performance, monthly revenue trends, and product category performance using Python and SQL.

## Objectives
- Analyze order statuses and data quality.
- Calculate revenue from delivered orders.
- Calculate Average Order Value (AOV).
- Identify monthly sales trends.
- Find the top product categories by revenue.
- Use SQL queries to validate business insights.

## Tools and Technologies
- Python
- Pandas
- SQLite
- SQL
- Matplotlib
- Jupyter Notebook

## Dataset
The project uses the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle.

The dataset includes order information, order items, product details, customer information, and product category translations.

## Key Findings
- **Delivered orders:** 96,478
- **Revenue from delivered items:** 15,322,498.11
- **Average Order Value (AOV):** 137.04
- **Highest-revenue month:** November 2017
- **Top product category by revenue:** Health and Beauty

*Note: Revenue is calculated using item prices for delivered orders and excludes freight charges. Results are based on the dataset and calculation methods used in this project.*

## Project Workflow
1. Loaded the datasets into Pandas DataFrames.
2. Checked missing values and duplicate records.
3. Converted order timestamps to datetime format.
4. Checked item prices and freight charges for missing or negative values.
5. Calculated revenue and Average Order Value.
6. Visualized monthly revenue using Matplotlib.
7. Analyzed top product categories by revenue.
8. Created an SQLite database and used SQL queries for analysis.

## How to Run the Project
1. Install Python.
2. Install the required libraries:

   ```bash
   pip install pandas matplotlib jupyter
   ```

3. Download the Olist dataset from Kaggle.
4. Place the required CSV files in the folder expected by the notebook.
5. Open `Ecommerce_Sales_Analysis.ipynb` in Jupyter Notebook.
6. Run the notebook cells in order.

## Repository Contents
- `Ecommerce_Sales_Analysis.ipynb` — notebook containing the analysis, SQL queries, and visualizations.
- `README.md` — project documentation.

## Conclusion
This project demonstrates how Python, Pandas, SQL, and data visualization can be used to analyze e-commerce sales data and extract useful business insights.

## Data Source
Olist Brazilian E-Commerce Public Dataset on Kaggle.

