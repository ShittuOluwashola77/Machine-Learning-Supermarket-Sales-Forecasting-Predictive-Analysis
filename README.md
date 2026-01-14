# :tada: Machine-Learning-Supermarket-Sales-Forecasting-Predictive-Analysis
This repository contains a Machine Learning pipeline designed to forecast total sales per transaction for a supermarket. By analyzing historical transaction data, the model identifies key drivers of revenue and provides actionable insights for inventory management and operational optimization.
##  :chart_with_upwards_trend: Dataset Description
The analysis is based on a dataset containing 1,000 transaction records. Key features include:
Transactional Data: Invoice ID, Date, Time, Payment method.
Customer Information: Customer type (Member/Normal), Gender.
Product Details: Product line, Unit price, Quantity.
Financials: Cost of Goods Sold (COGS), Tax (5%), Gross Income, and the target variable Sales.
Feedback: Customer Rating.

##  :hammer: Data Processing and Feature Engineering

Temporal Extraction: Converted raw date and time strings into actionable features: Hour, DayOfWeek, and Month.

Data Cleaning: Performed initial inspection for missing values and confirmed the dataset's structure using descriptive statistics.

## :microscope: Exploratory Data Analysis (EDA)

Sales Distribution: A histogram analysis was performed to understand the central tendency and spread of transaction values.

Categorical Analysis: Explored how sales fluctuate across different product lines, cities, and customer types.

## :bulb: Model Results & Insights

Primary Predictors: The model identified that Tax 5%, gross income, and cogs are the most influential features, as expected from their direct relationship with sales.

Secondary Drivers: Beyond direct financial calculations, Unit price, Quantity, and Rating were key factors in predicting total transaction value.

Operational Trends: Time-based features like Hour and DayOfWeek showed significant variations in average sales, providing a roadmap for staffing optimization.

## :hammer: Business Recommendations

Inventory Optimization: Focus on stock management for high-unit-price items and popular product lines to maximize transaction totals.

Strategic Staffing: Align staffing levels with peak hours and days identified through temporal analysis.

Targeted Marketing: Implement campaigns tailored to the specific customer types and cities that demonstrate the highest average sales.
