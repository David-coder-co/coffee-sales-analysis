# Coffee Sales Analysis
## INTRODUCTION
This repository focuses on the analysis of coffee sales transactions from a vending machine. The dataset provides detailed records of purchases, allowing for an in-depth examination of sales trends, customer preferences, and purchase behaviors.

### Data Collection Period
- The dataset spans from March 2024 to Present, capturing daily transaction data.
- New sales data continues to be added over time.

### Dataset Description
The dataset contains the following columns:
- date – The transaction date.
- datetime – The exact date and time of the purchase.
- cash_type – Indicates if the purchase was made via cash or card.
- card – The ID of the card used for the transaction (for tracking purchases).
- money – The amount spent in the transaction.
- coffee_name – The specific coffee product purchased.

### Tasks and Analysis Performed
- Time Series Exploratory Data Analysis (EDA): Explored the dataset to understand sales trends, identify seasonal patterns, and detect anomalies.
- Sales Forecasting: Using ARIMA modeling to predict future sales on a daily, weekly, and monthly basis.
- Customer Purchase Analysis: Analyzed customer purchase frequency, popular coffee types, and transaction behavior.

### Technologies Used
- Python: The primary programming language for analysis and modeling.
- pandas: Used for data manipulation, such as handling missing values, filtering data, and performing group operations. Missing values in the dataset were handled by filling with 'cash' where appropriate.
- Matplotlib/Seaborn: Used for data visualization to plot sales trends, customer behavior, and forecast results.
- Statsmodels (ARIMA): Used to train an ARIMA model for time series forecasting.

### How to Use
- Clone this repository to your local machine.
- Install required dependencies using the following command: pip install -r requirements.txt
- Run the analysis by executing the coffee_sales.ipynb script.
- The script will generate visualizations and predictions based on the dataset provided.
