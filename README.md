# Challenge5_Repo
Challenge 5 Repo - Building a tool to help credit union members evaluate their financial health


# User Story
Role: FinTech Consulting Firm

Goal: The project goal is develop a prototype application to help credit union members evaluate their financial health. 
      The tool should enable the following: 
      1. They should be able to assess their monthly budgets. 
      2. They should be able to forecast a reasonably effective retirement plan based on their current holdings of cryptocurrencies, stocks, and bonds. 

Reason: The credit union focus is on projects that will benefit local communities offering them the opportunity to achieve the following:
      1.	Enable members to determine if they have enough reserves for an emergency fund.
      2.	A financial planner for forecasting and visualizing the performance of their retirement portfolio in 30 years. 

# General information about the analysis
•	The average monthly household income for each credit union member is $12,000.
•	Each credit union member has a savings portfolio that consists of a cryptocurrency wallet, stocks/bonds.


# Technology
Jupyter notebook that contains data preparation, analysis, and visualizations for key risk and return metrics. 
Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.
GitHub repository Python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
# Libraries used in the analysis
• A single DataFrame imported from a CSV file that has a DateTimeIndex.
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

# Analysis
Evaluate the Cryptocurrency Wallet by Using the Requests Library 
Evaluate the Stock and Bond Holdings by Using the Alpaca SDK
Evaluate the Emergency Fund
Create a Financial Planner for Retirement
Analyze the Retirement Portfolio Forecasts
Create the Monte Carlo Simulation 
Forecast Cumulative Returns in 10 Years


