# Challenge_5
The purpose of this project was to pull live prices from Alpaca API




# Tech
Financial Analysis using the following libaries and dependencies import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
%matplotlib inline
These tools can be viewed in Jupyter Lab or Jupyter Notebook


## Tools
 A financial planner for emergencies. The members will be able to use this tool to visualize their current savings. The members can then determine if they have enough reserves for an emergency fund.
 A financial planner for retirement. This tool will forecast the performance of their retirement portfolio in 30 years. To do this, the tool will make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations.

# Intructions
1. Download financial_planning_tools.ipynb
2. User must add their own values into sample.ENV and save to a .env to enable access for live data from Alpaca API
