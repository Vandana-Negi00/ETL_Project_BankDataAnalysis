# Bank Market Capitalization ETL and Data Analysis

## Project Overview

This project implements an **ETL (Extract, Transform, Load) pipeline** to collect, process, and analyze data on the world's largest banks by market capitalization. The project demonstrates how raw data from web sources can be extracted, cleaned, transformed, and analyzed using **PySpark and Python**.

The final dataset is used to perform exploratory data analysis and visualization to understand trends in global banking market capitalization.

---

## Objective

The objective of this project is to:

* Extract banking data from a web source
* Clean and transform the dataset using PySpark
* Perform data quality checks including missing value detection and duplicate handling
* Analyze the market capitalization distribution of global banks
* Visualize key insights using Python data visualization libraries

---

## Data Sources

The project uses two main data sources:

1. **Wikipedia dataset**

List of largest banks by total assets extracted from an archived Wikipedia page.

2. **Exchange rate dataset**

CSV file containing currency exchange rates used for financial data processing.

---

## Tools and Technologies

The project uses the following tools:

* Python
* PySpark
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## ETL Pipeline

### Extract

* Data extracted from a Wikipedia webpage using pandas.
* Exchange rate dataset loaded from a CSV file.

---

### Transform

Several data transformation steps were performed:

* Conversion of Pandas DataFrame to PySpark DataFrame
* Column renaming and schema inspection
* Handling missing values
* Removing duplicate records
* Outlier detection using statistical techniques

---

### Load

The cleaned dataset is exported for further analysis.

Example output file:

```
banks_market_cap_cleaned_df.csv
```

---

## Data Analysis

Exploratory data analysis was performed on the cleaned dataset to understand:

* Distribution of bank market capitalization
* Ranking of banks by market cap
* Presence of outliers in financial data
* Market cap segmentation using quartiles

---

## Visualizations

The project includes the following visualizations:

* Market capitalization distribution
* Top 10 banks by market capitalization
* Market cap vs bank ranking
* Boxplot showing market cap spread
* Quartile distribution analysis

---

## Project Structure

```
bank-market-cap-etl
│
├── ETL-Project-Bank-Data-Analysis.ipynb
├── ETL-project-BankDataAnalysis-Report.pdf
└── README.md
```

---

## Author

Vandana Negi

---
