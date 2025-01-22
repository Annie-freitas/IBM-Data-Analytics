Web Scraping

This project extracts and analyzes stock data for Tesla (TSLA) and GameStop (GME). 
The goal is to practice data extraction, data manipulation, and visualization skills using real-world financial data. 
This project includes the extraction of stock data and revenues, data processing (such as removing commas and dollar signs), and the plotting of stock price trends.
This allows us to visualize trends in Tesla and GameStop stock prices from publicly available resources.

Features
Data Extraction:
Using requests and BeautifulSoup, stock data for Tesla and GameStop was scraped from a financial website.

Data Cleaning:
After extracting the data, the Revenue columns were cleaned by removing dollar signs and commas to ensure that the numbers could be analyzed properly.

Data Analysis:
Stock data for Tesla and GameStop were analyzed up to June 2021. The Date and Close prices were used for trend analysis.

Visualization:
We used matplotlib to create stock price plots for both Tesla and GameStop, allowing for visualization of stock price movements and trends over time.


Tools and Libraries Used
requests: For making HTTP requests to fetch web data.
BeautifulSoup: For parsing and extracting data from HTML documents.
pandas: For data manipulation and analysis, especially for handling tables and time series data.
yfinance: For extracting financial data (e.g., stock data) from Yahoo Finance.
matplotlib: For creating stock price plots and other visualizations.
