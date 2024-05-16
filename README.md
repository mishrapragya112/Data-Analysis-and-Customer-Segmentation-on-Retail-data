# Exploratory Data Analysis and Customer Segmentation on Retail Data
## Author: Pragya Mishra
Date: 16-05-24

## Overview
This notebook provides an exploratory data analysis (EDA) and customer segmentation for retail data. The goal is to uncover insights about sales, profit, product performance, and customer segments using various visualizations and data analysis techniques.

## Table of Contents
Introduction and Setup
Data Loading and Initial Exploration
Data Understanding
Data Preprocessing
Exploratory Data Analysis (EDA)
Sales and Profit Analysis
Geographical Analysis
Product Analysis
Segment Analysis
Customer Segmentation
Conclusion

## Introduction and Setup
This section includes the setup of the environment and the importation of necessary libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

## Data Loading and Initial Exploration
The retail dataset is loaded from an Excel file. Initial exploration includes viewing the first few rows of the dataset to understand its structure and contents.

## Data Understanding
In this section, the shape of the data is determined, revealing the number of rows and columns. Missing values, unique values, and data types are checked to understand the quality and nature of the data.

## Data Preprocessing
Date columns (Order Date and Ship Date) are converted to datetime objects. Additional columns such as Order Year and Order Month are created from the Order Date to facilitate time-based analysis.

## Exploratory Data Analysis (EDA)
Sales and Profit Analysis
Sales and Profit by Category: A bar plot shows the total sales and profit for each product category.
Sales and Profit by Sub-Category: Another bar plot visualizes sales and profit for different product sub-categories.
Geographical Analysis
Sales and Profit by State: A choropleth map visualizes sales and profit across different states.
Top 10 Cities by Sales and Profit: Bar plots show the sales and profit for the top 10 cities.
Product Analysis
Top 10 Products by Sales and Profit: Pie charts and bar plots show the sales and profit for the top 10 products.
Segment Analysis
Sales and Profit by Segment: Pie charts show the distribution of sales and profit across different customer segments.
Customer Segmentation
Customer segmentation is performed using clustering techniques to segment customers based on their purchasing behavior.

## Conclusion
The notebook provides a thorough exploration and analysis of the retail data, using a variety of visualizations to uncover insights about sales, profit, product performance, and customer segments. These insights can help the company focus on high-performing categories, optimize pricing and cost strategies, and tailor marketing efforts to key customer segments and geographical regions.

