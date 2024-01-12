# Understanding crypto currency price fluctuations
How do crypto-currencies behave? What factors affect them? I scrape the data from some websites, use APIs of others and CSVs to understand the impact by visualizing all on a streamlit dashboard.

### Sources of Data

Data | Source | Type
----- | ----- | --------
| 1. Tweet | Twint | Web Scraping
| 2. Crypto-currency prices | Coingecko | API
| 3. S&P 500 Data (Stock Exchange Indicator) | Yahoo Finance | API
| 4. Crypto News | Coindesk | Web Scraping
| 5. Business Confidence Index (macro-economic indicator) | Organization for Economic Co-operation and Development | CSV


### Methodology
Collect > Clean > Integrate

1) Numerical Scaling. Introduced a lag to analyze how they correlate with prices.
2) Analyzed the Twitter data and ran a sentiment analysis
3) Integrated all the data
4) Constructed a dashboard to analyze the fluctuations and what factors they were correlated with


