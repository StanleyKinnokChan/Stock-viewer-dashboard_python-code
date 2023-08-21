# Stock-viewer-dashboard_python-code

This is the python script used to capture the S&P500 stock data, which were then used to create the Tableau stock viewer dashbaord. 
The script captured OHLC data from 2000 to 2023, as well as the company metrics eg P/E ratio, market cap, dividentd yield, ROA....

The script itself is idempotent, which can be downloaded and executed directly multiple times to update the stock data, without changing the columns and calculation.  
