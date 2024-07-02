# Stock price data analysis using Pyspark

# Project Overview
This project aims to analyze the stock price data of the 'Magnificent Seven' companies and the S&P 500 index to derive meaningful insights. 
Using PySpark, we preprocess the data, create various financial features, and apply multiple regression models to predict stock prices. 
The project also includes a comparative analysis of these predictions against the actual stock prices and the broader market index (S&P 500).

# Parameters analyzed 
1. Average Closing Price: The average price at which the stock has closed over the analyzed period.
2. Maximum Closing Price: The highest recorded closing price.
3. Minimum Closing Price: The lowest recorded closing price.
4. Standard Deviation of Closing Price: Measures the volatility of the stock's closing price.
5. Average Volume: The average number of shares traded daily.
6. Maximum Volume: The highest recorded trading volume in a single day.
7. Minimum Volume: The lowest recorded trading volume in a single day.
8. Standard Deviation of Volume: Measures the volatility in trading volume.
9. Price Range : The difference between the maximum and minimum closing prices.
10. 30-Day Moving Average: A common technical indicator used to smooth out price data by creating a constantly updated average price over a 30-day period.
11. Daily Return: The daily percentage change in closing price, representing the day-to-day price momentum.
12. Volatility: Standard deviation of the daily return over a 30-day period.
13. Average Daily Volume: Measures the average trading activity.
14. Comparison of Returns vs. S&P 500: Analyzes how the individual stock returns compare to the broader market index (S&P 500).
15. Correlation Matrix of Closing Prices: Measures how the closing prices of different stocks are correlated.

# Results
The analysis revealed various insights into the stock price behavior of the Magnificent Seven companies. 
The Gradient Boosting Trees (GBT) model generally outperformed other models in terms of lower RMSE, indicating better predictive performance. 
The correlation matrix helped identify the relationships between different stocks, showing how they move in relation to each other. 
Visual comparisons of stock returns against the S&P 500 provided a broader market context for individual stock performance.

# Installation 
 - Clone the repository
 - Install the requirements "pip install -r requirements.txt"
 - Ensure that you have Pyspark installed and configured
