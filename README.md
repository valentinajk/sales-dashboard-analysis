Sales Dashboard Analysis — Superstore Dataset

This project is an end-to-end sales analysis using Python, Pandas, Matplotlib, Seaborn, and Jupyter Notebook.  
The goal is to understand sales performance, profit behavior, category trends, regional performance, and the impact of discounts using the Superstore dataset.

-------------------------------------------------------------------

Project Structure
```
salesdatareport/
│
├── data/
│   ├── Sample - Superstore.csv
│   └── cleaned_superstore.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_visualizations.ipynb
│
├── images/
│   ├── monthly_sales_trend.png
│   ├── category_sales.png
│   ├── profit_by_region.png
│   ├── discount_vs_profit.png
│   ├── top10_subcategories.png
│   ├── top10_products.png
│   ├── correlation_heatmap.png
│   ├── yearly_sales_trend.png
│   └── quantity_distribution.png
│
├── requirements.txt
└── README.md
```
-------------------------------------------------------------------

Objective

The aim of this project is to analyze the Superstore dataset and explore:

- Monthly and yearly sales patterns  
- Best and worst performing product categories  
- Regional profit variations  
- Impact of discounting on profit  
- Top-performing products and sub-categories  
- Key relationships between sales, profit, quantity, and discount  

-------------------------------------------------------------------

Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

-------------------------------------------------------------------

1. Data Cleaning

Performed in the notebook "01_data_cleaning.ipynb".  
Key steps included:

- Standardizing column names  
- Converting date columns to datetime format  
- Creating new fields (order_year, order_month, profit_margin)  
- Checking for missing values and duplicates  
- Exporting the cleaned dataset as "cleaned_superstore.csv"

---------------------------------------------------
