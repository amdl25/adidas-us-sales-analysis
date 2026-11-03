# Adidas US Sales Analysis – Excel Dashboard

Statistical analysis and interactive Excel dashboard of **9,648 Adidas sales transactions** in the United States (2020–2021), covering **$899.9M in total sales** and **$332.1M in operating profit**.

The workbook content is in Romanian.


## Objectives

1. Describe the sales data through descriptive statistical indicators and their interpretation.
2. Build an interactive dashboard with pivot tables, charts, slicers and a timeline.
3. Draw conclusions about Adidas product performance across regions, retailers, products and sales channels.

## Dataset

Source: [Adidas Sales Dataset – Kaggle](https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset)

| Variable type | Columns |
|---|---|
| Qualitative | Retailer, invoice date, region, state, city, product, sales method |
| Quantitative | Price per unit, units sold, total sales, operating profit, operating margin |

## Workbook structure

| Sheet | Contents |
|---|---|
| **Introducere** | Project overview, objectives, variables and a linked table of contents |
| **Dashboard** | KPI cards (`GETPIVOTDATA`) and a pivot table of sales by region, retailer and product, filtered by 5 slicers and a timeline |
| **Date** | The dataset (9,648 rows) |
| **Statistici descriptive** | Mean, standard error, median, mode, standard deviation, variance, kurtosis, skewness, range, min, max, sum and count for each quantitative variable, with interpretations |
| **Box plot** | Quartiles, outlier fences and box plots for all quantitative variables, with interpretations |
| **Analize pivot** | 6 pivot tables with pivot charts (see below) |

### Pivot analyses

1. Total sales by region and product (filter: sales method)
2. Average price per unit by product and retailer
3. Monthly sales performance (filter: region)
4. Average operating margin by retailer and sales method
5. Top 10 cities by total sales
6. Best product–retailer combinations, with share of sales


## Key insights

- **West** is the largest region, with 30% of total sales.
- **Men's Street Footwear** is the best-selling product (23% of sales).
- **West Gear** is the top retailer (27% of sales).
- **Online** sales have the highest average operating margin (46.4%), versus 35.6% for in-store.
- **Charleston** and **New York** are the cities with the highest sales (about $40M each).
- Sales and profit are strongly right-skewed: the median transaction is $9,576, while the mean is $93,273.


## Excel skills used

Pivot tables · pivot charts · slicers · timeline · Analysis ToolPak (descriptive statistics) · box plots

## How to use

Download [`excel/adidas_sales_analysis.xlsx`](excel/adidas_sales_analysis.xlsx) and open it in desktop Excel (2016 or later). GitHub cannot preview Excel files, and the slicers and timeline only work in desktop Excel. Start on the **Dashboard** sheet and use the slicers to filter the data.

The dataset is also available as CSV in [`data/vanzari_adidas_sua.csv`](data/vanzari_adidas_sua.csv).

## Repository structure

```
├── adidas_sales_analysis.xlsx   # Excel project and dashboard
├── adidas_sales_original.csv        # dataset
└── README.md
```
