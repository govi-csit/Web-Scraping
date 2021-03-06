# Yahoo Finance : Fetch Stock Maket Data

## Description : 
Yahoo Finance is the largest business and financial news site in the world, with unrivaled access to data, insights, and content. It provides financial news, data and commentary including stock quotes, press releases, financial reports, and original content.
## Problem Statement: 
Fetch stock market data from Yahoo Finance for all List of S&P 500 companies.
## Sources / useful links
**Tickert Symbol:**
A *Ticker symbol* or *Stock symbol* is an abbreviation used to uniquely identify publicly traded shares of a particular stock on a particular stock market. Ticker symbols vary depending on what stock market they are traded on. They can consist of letters, numbers, or a combination of both. Sometimes they are also called *stock symbols*.

Some examples of US Stock symbols include:  
•	AAPL – Apple  
•	GOOG – Alphabet Inc.  
•	HOG – Harley-Davidson  
•	HPQ - Hewlett-Packard  
•	INTC – Intel  
•	KO – The Coca-Cola Company  
•	MSFT – Microsoft  
•	WMT – Walmart  

Ticker Symbols source : https://en.wikipedia.org/wiki/List_of_S%26P_500_companies  
Stock market data source : https://finance.yahoo.com/quote/MMM?p=MMM  

## Approach: 
1.	Fetch stock market data for a single company using Ticker Symbol
2.	Collect Ticker Symbols for all the List of S&P 500 companies from https://en.wikipedia.org/wiki/List_of_S%26P_500_companies
3.	Fetch stock market data for all S&P 500 companies by varying the ticker symbol in the URL : https://finance.yahoo.com/quote/MMM?p=MMM


### Output
The final ouput will be exported into csv file : yahoo_finance_data.csv
