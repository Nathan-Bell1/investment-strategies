# learn-strategic-investing
📊 learn-strategic-investing
This project is a hands-on application of quantitative investing strategies using Python, Pandas, and financial data from Yahoo Finance. Inspired by freeCodeCamp’s curriculum, I built and customized three full investment strategy pipelines in Jupyter notebooks, each exporting clean, structured output to Excel.

Along the way, I developed deeper skills in:

📦 Anaconda & Jupyter for environment and code management

🐼 Pandas for data manipulation and ranking

📈 Financial metrics and modeling

🔍 Data scraping from Yahoo Finance with yfinance

📊 Excel output formatting with openpyxl

📁 Project Structure
Equal_Weight_Strategy.ipynb
Selects the top 50 stocks from the S&P 500

Calculates how many shares to buy for each, based on a fixed portfolio size

Equal capital allocation across all selected stocks

Quantitative_Momentum_Strategy.ipynb
Ranks all S&P 500 stocks by momentum over 1, 3, 6, and 12 months

Scores and weights momentum performance

Selects top performers for portfolio allocation

Quantitative_Value_Strategy.ipynb
Ranks all S&P 500 stocks by value factors:

Price-to-Earnings (P/E)

Price-to-Sales (P/S)

Price-to-Book (P/B)

EV/EBITDA (Enterprise Value / EBITDA)

EV/GP (Enterprise Value / Gross Profit)

Combines rankings into a composite value score

Allocates equally across top-value stocks

🧰 Tech Stack
Python

Jupyter Notebook

Pandas

yfinance

openpyxl

Excel

Anaconda

⚠️ Disclaimer
