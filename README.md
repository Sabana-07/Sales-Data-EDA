Sales Data Exploratory Data Analysis (EDA)

📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on sales data from 2015 to 2019 to uncover trends, patterns, and insights that can support business decision-making. The analysis includes data cleaning, visualization, and deriving key insights about sales performance across time, products, and regions.

🎯 Objectives
Understand overall sales performance over multiple years

Identify key factors influencing sales trends

Detect seasonal patterns and anomalies

Provide actionable recommendations for improving sales strategy

📂 Dataset
Files: 2015.xls, 2016.xls, 2017.xls, 2018.xls, 2019.xls

Source: Kaggle Sales Forecasting Dataset

Key Features:

Product_ID – Unique product identifier

Customer_ID – Customer reference ID

Sales – Sales amount

Date – Transaction date

Region – Sales region

Category – Product category

🛠 Tools & Libraries Used
Python

NumPy – Numerical operations

Pandas – Data cleaning & manipulation

Matplotlib – Data visualization

Seaborn – Advanced plots & visual styling

🔍 EDA Process
Data Cleaning

Removed duplicates

Converted date columns to datetime format

Fixed inconsistent data types

Handled missing values

Univariate Analysis

Sales distribution histograms

Regional sales bar charts

Top products and categories

Bivariate Analysis

Sales by postal code

Scatter plots for relationships

Correlation heatmaps

Advanced Visualizations

Joint plots to explore variable relationships

📈 Key Insights
Identified top-performing regions and categories

Discovered seasonal patterns in sales data

Found strong correlations between certain product categories and high sales volumes

🚀 How to Run the Notebook
Clone this repository:

git clone https://github.com/Sabana-07/Sales-Data-EDA.git
Install dependencies:


pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook:

jupyter notebook "Sales Data EDA.ipynb"
