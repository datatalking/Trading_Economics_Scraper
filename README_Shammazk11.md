# README

We are aggregating data from multiple websites
economic data and market data = https://tradingeconomics.com
market company data = http://en.wikipedia.org/wiki/List_of_S%26P_500_companies
market data = https://www.cboe.com/us/options/market_statistics/symbol_data/?mkt=cone

lookback_data = https://www.statista.com/statistics/1251763/sandp-500-best-performing-stocks/

0. We are expanding our stock market algorithm, if you would like to help long term we can give you a percentage ownership in this venture. You help with python, sql and we give you say 5% of the company?
1. mstables can create a SQLite database.
2. bs4_html_scraper_2.ipynb can access a website to scrape
3. There are url strings we need to iterate through like 'https://tradingeconomics.com/commodities'
4. we need to save each iteration with that days date, url to url10. (need to cycle through these and more urls I will add in the future)
5. we need to save each iteration with that days data
6. we need to cycle through each iteration each day
7. We need to cycle through each 'markets', 'indicators', 'forcast' from https://tradingeconomics.com
8. look at what it downloads and document how much of the morningstar mstable database is filled with the tradingecnomics
9. if mstable exceeds trading economics this is good, expand the database.
10. install https://github.com/datatalking/yahoo_finance_Sp500_scrape/tree/master/yahoo_scrape
11. start one of the yahoo_scrape notebooks
12. Download data from yahoo_scrape, save along side mstables
13. Note where we have duplicates
14. allow for csv imports for the same values from yahoo_scrape, mstables and trading economics
15. can you improve the bs4_html_scraper_2.ipynb to scrape data also from https://www.cboe.com/us/options/market_statistics/symbol_data/?mkt=cone
16. Message me with questions as an issue https://github.com/datatalking/Trading_Economics_Scraper/issues/1
