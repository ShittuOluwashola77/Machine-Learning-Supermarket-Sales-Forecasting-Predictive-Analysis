# :tada: Machine-Learning-Supermarket-Sales-Forecasting-Predictive-Analysis
This repository contains a Machine Learning pipeline designed to forecast total sales per transaction for a supermarket. By analyzing historical transaction data, the model identifies key drivers of revenue and provides actionable insights for inventory management and operational optimization.
# :chart_with_upwards_trend: Dataset Description
The analysis is based on a dataset containing 1,000 transaction records. Key features include:
Transactional Data: Invoice ID, Date, Time, Payment method.
Customer Information: Customer type (Member/Normal), Gender.
Product Details: Product line, Unit price, Quantity.
Financials: Cost of Goods Sold (COGS), Tax (5%), Gross Income, and the target variable Sales.
Feedback: Customer Rating.

# :hammer: Data Processing and Feature Engineering

Temporal Extraction: Converted raw date and time strings into actionable features: Hour, DayOfWeek, and Month.

Data Cleaning: Performed initial inspection for missing values and confirmed the dataset's structure using descriptive statistics.
