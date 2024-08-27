# Credit Card Default Dashboard and EDA

## Project Overview & Purpose

This project consists of two main components: an Exploratory Data Analysis (EDA) using Python, Pandas and an interactive dashboard. We analyzed credit card usage patterns, payment behaviors, and default risks using a dataset from the UCI Machine Learning Repository. The analysis covers default payments, late payments, demographic factors, credit utilization ratio data, payment history, and bill statements of credit card clients. The purpose of this project is to analyze payment and spending patterns within a credit card dataset, with a specific focus on identifying default and late payment patterns. 

## Features

### Exploratory Data Analysis (EDA)
- Data extraction and cleaning
- Statistical analysis of credit card usage patterns
- Correlation studies between various factors and default/late payments
- Correlation between credit utilization ratio with various factors
- Visualization of key trends and insights

### Interactive Dashboard
- Late Payment Analysis
- Buying Pattern Behavior Visualization
- Demographic Insights
- Credit Utilization Ratio Examination
- The 'Filter by' is a global drop down menu that consist of default, gender, marital status, age group & education

## Data Source

The dataset is sourced from the UCI Machine Learning Repository's "Default of Credit Card Clients Dataset", containing information on 30,000 credit card clients in Taiwan.

## Project Components

### 1. Exploratory Data Analysis (EDA)
- **Data Extraction**: Importing and initial processing of the dataset
- **Data Cleaning**: Handling missing values, outliers, and data inconsistencies
- **Statistical Analysis**: Descriptive statistics, distribution analysis, correlation studies
- **Data Visualization**: Creating informative plots and charts for key insights

### 2. Interactive Dashboard
- Dynamic visualizations of EDA findings
- Filtering options for data segmentation
- Summary statistics and key metrics display

## Technologies Used

- **Data Processing and Analysis**: 
  - Python
  - Pandas
  - Numpy
    
- **Data Visualization**: 
  - Matplotlib
  - Seaborn (for EDA)
  - D3.js (for interactive dashboard visualizations)
    
- **Frontend Development**:
  - HTML
  - JavaScript
  - Tailwind CSS (for styling)

## Dashboard

You can view our interactive dashboard here: [Credit Card Default Dashboard](https://j91k.github.io/Credit_Card_Default_Dashboard/)

Three graphs are displayed at Default

- Late Payments (histogram of the number of customers (vertical) with the number of late payments (horizontal) over the 6-month period of the dataset)
- Credit Score (histogram of the number of customers (vertical) with a credit utilization ratio of above 30% or below 30%)
- Average Bill Amount (line graph of average monthly credit card bill balance in dollars (vertical) for each month (horizontal) for each of the 6 age groups in the legend)

To display details by demographic characteristic
Choose the drop down “Filter by:”

All = default
Gender
Marital status
Age group
Education Level

To disaggregate the “Late Payments” by number of late payments
Choose the drop down “Select Late Payments

To disaggregate the “Credit Score” by above 30% or below 30%
Choose the drop down “Credit Score Filter”

## Data Ethics Concern

When working with the financial dataset, we have prioritized ethical considerations related to privacy, security, and transparency. Although the dataset is anonymized, it contains sensitive information such as financial transactions and credit card payment details. We ensured that our analysis respected privacy by refraining from any attempts to re-identify individuals and secured the dataset to prevent unauthorized access. Additionally, we carefully examined the data for potential biases to avoid any unfair impact on certain groups, particularly based on demographic or socioeconomic factors. By adhering to these principles, we have aimed to maintain integrity and fairness in our analysis.

## Team Members

- Jimmy Kim
- Ernawaty Ernawaty
- Mounika Lingala
- Judy Pin
- Thet Win


