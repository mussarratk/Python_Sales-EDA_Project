# Festival Sales Dataset - Data Analysis Project

## Overview
The "Festival Sales Dataset" data analysis project aims to provide valuable insights into consumer behavior and sales trends during festival shopping. This repository contains the dataset, Python code, and visualizations used for the analysis.

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![numpy](https://img.shields.io/badge/numpy-1.21.2-blue)](https://numpy.org/)
[![pandas](https://img.shields.io/badge/pandas-1.3.3-blue)](https://pandas.pydata.org/)
[![matplotlib](https://img.shields.io/badge/matplotlib-3.4.3-blue)](https://matplotlib.org/)
[![seaborn](https://img.shields.io/badge/seaborn-0.11.2-blue)](https://seaborn.pydata.org/)

## Table of Contents
- [Python Libraries](#python-libraries)
- [Data Loading](#data-loading)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Gender Analysis](#gender-analysis)
  - [Age Analysis](#age-analysis)
  - [State Analysis](#state-analysis)
  - [Marital Status Analysis](#marital-status-analysis)
  - [Occupation Analysis](#occupation-analysis)
  - [Product Category Analysis](#product-category-analysis)
- [Conclusion](#conclusion)

## Python Libraries
The following Python libraries were used for data analysis:
- numpy
- pandas
- matplotlib.pyplot
- seaborn

## Data Loading
The dataset was loaded using the pandas library from the CSV file named "Festival Sales Data.csv".

## Data Preprocessing
- Irrelevant columns "Status" and "unnamed1" were dropped from the dataset.
- Null values in the dataset were dropped to ensure data quality.
- The data type of the "Amount" column was changed to integer for further analysis.

## Exploratory Data Analysis
The dataset was analyzed using various visualizations to gain insights into consumer behavior and sales trends during festival shopping.

### Gender Analysis
- A bar chart was plotted to visualize the count of buyers based on their gender.
- Another bar chart was plotted to compare the total purchase amount between genders.

### Age Analysis
- A bar chart was plotted to visualize the count of buyers based on their age group and gender.
- Another bar chart was plotted to compare the total purchase amount for each age group.

### State Analysis
- Bar charts were plotted to show the total number of orders and total sales amount from the top 10 states.

### Marital Status Analysis
- A bar chart was plotted to visualize the count of buyers based on their marital status.
- Another bar chart was plotted to compare the total purchase amount for each marital status and gender.

### Occupation Analysis
- A bar chart was plotted to visualize the count of buyers based on their occupation.
- Another bar chart was plotted to compare the total purchase amount for each occupation.

### Product Category Analysis
- Bar charts were plotted to show the count of products sold in each product category and the total sales amount for the top 10 product categories.
- A bar chart was plotted to show the count of orders for the top 10 most sold products.

## Conclusion
Based on the analysis of the "Festival Sales Dataset," the following conclusions were drawn:
- Majority of buyers are female, and their purchasing power is greater than that of males.
- Most buyers are aged between 26-35 years, and they are primarily female.
- Uttar Pradesh, Maharashtra, and Karnataka are the top states contributing to most orders and total sales amount.
- Married women have higher purchasing power compared to other groups.
- Buyers working in IT, Healthcare, and Aviation sectors are the most active shoppers.
- Food, Clothing, and Electronics are the most popular product categories.

Please note that these conclusions are based on the dataset and analysis performed on it. For any further insights or specific recommendations, more extensive analysis and additional data may be required.


## How to Use
1. Clone this repository to your local machine.
2. Ensure you have the required Python libraries installed.
3. Run the Jupyter Notebook (sales_project_analysis.ipynb) to perform the analysis.

Feel free to contribute and open issues if you encounter any problems or have suggestions for improvement.

Happy data analysis!
