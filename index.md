## Finnhub Stock API - Global fundamentals, market data and alternative data

Finnhub is an American company with people working in New York, Mumbai, Sydney, and Ho Chi Minh to source, clean and serve the right financial data to our customers. With data centers around the globe and a diverse workforce, Finnhub provide high quality data with easy access to the biggest clients in the industry ranging from hedge funds, mutual funds to investment banks and S&P companies.

With the mission of democratizing financial data, Finnhub is proud to offer a FREE retail-focus realtime API for stocks, forex and cryptocurrency. With this API, you can access realtime market data from global stock exchanges, 10 forex brokers, and 15+ crypto exchanges. Finnhub also provides institutional-grade alternative and fundamental data for global companies through our stock API. Finnhub is ranked number 1 on Towards Data Science stock API guide. See why Finnhub is the leader in financial data APIs with this comparision.



Data provided on [Finnhub Stock API](https://finnhub.io/):

# Global Fundamental Data:

  - Global Company Profile

  - Company Executives

  - Company Ownership

  - Standardized financial statements

  - Financials As Reported

  - Dividends

  - IPO calendar

# Market Data

  - Real-time stock API

  - Tick Data

  - Forex

  - Crypto

# Estimates

  - Price Target

  - Recommendation trends

  - EPS estimates

  - Revenue estimates

  - Earnings Calendar

# Alternative Data

  - Earnings call transcripts with audio from 2000

  - Covid-19 data

  - Real-estate pricing

  - Merger and Acquisitions for public and private market

  - Supply chain

With global coverage and deep historical data, [Finnhub Stock API](https://finnhub.io/) provides an unparalleled API for global investors, investment firms and fintech startups.

### Markdown
```
import finnhub
finnhub_client = finnhub.Client(api_key="YOUR API KEY")

res = finnhub_client.stock_candles('AAPL', 'D', 1590988249, 1591852249)
print(res)

import pandas as pd
print(pd.DataFrame(res))

print(finnhub_client.aggregate_indicator('AAPL', 'D'))

[Link](url) and ![Image](src)
```


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://finnhub.io/docs/api#company-profile)
