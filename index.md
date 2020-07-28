## Finnhub Stock API - Global fundamentals, market data and alternative data

Finnhub is an American company with people working in New York, Mumbai, Sydney, and Ho Chi Minh to source, clean and serve the right financial data to our customers. With data centers around the globe and a diverse workforce, Finnhub provide high quality data with easy access to the biggest clients in the industry ranging from hedge funds, mutual funds to investment banks and S&P companies.

With the mission of democratizing financial data, Finnhub is proud to offer a FREE retail-focus realtime API for stocks, forex and cryptocurrency. With this API, you can access realtime market data from global stock exchanges, 10 forex brokers, and 15+ crypto exchanges. Finnhub also provides institutional-grade alternative and fundamental data for global companies through our stock API. Finnhub is ranked number 1 on Towards Data Science [stock API guide](https://medium.com/@andy.m9627/the-ultimate-guide-to-stock-market-apis-for-2020-1de6f55adbb). See why Finnhub is the leader in financial data APIs with this comparision.

![Finnhub Stock API](https://static.finnhub.io/img/Screen%20Shot%202020-07-25%20at%207.47.01%20PM.png)

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

With global coverage and deep historical data, [Finnhub Stock API](https://finnhub.io/) provides an unparalleled API for global investors, investment firms and fintech startups. A tutorial to build your own charts [powered by Finnhub](https://medium.com/@andy.m9627/build-your-own-tradingview-chart-for-global-stock-markets-right-on-your-site-with-tradingview-js-9e09252ed3b0)

### Markdown
```
import finnhub
finnhub_client = finnhub.Client(api_key="YOUR API KEY")

res = finnhub_client.stock_candles('AAPL', 'D', 1590988249, 1591852249)
print(res)

import pandas as pd
print(pd.DataFrame(res))

print(finnhub_client.aggregate_indicator('AAPL', 'D'))

```


### Support or Contact

Having trouble with Pages? Check out our [documentation](https://finnhub.io/docs/api#company-profile)
Join Finnhub's dicussion on:

- [Finnhub's Twitter](https://twitter.com/Finnhub_io)
- [Finnhub's Facebook](https://www.facebook.com/Finnhub-109587983789885)
- [Finnhub's Linkedin](https://www.linkedin.com/company/51658500)
- [Finnhub's Reddit](https://www.reddit.com/r/FinnhubAPI/comments/hjvm6b/finnhub_api_the_new_standard_for_financial_api/)
- [Finnhub's Kickstarter](https://www.kickstarter.com/projects/finnhub-stock-api/finnhub-free-stock-api-for-investors/description)  to help raise awareness amongst "builders" community.
- [Finnhub's Indiegogo](https://www.indiegogo.com/projects/finnhub-institutional-grade-stock-api/x/19059850#/) to help raise awareness amongst "builders" community.
- [Finnhub featured on Columbia University's quant community page](http://www.columbia.edu/~tmd2142/free-stock-api.html)
- [Finnhub - earnings call transcripts analysis](http://www.columbia.edu/~tmd2142/finnhub-api-earnings-call-transcripts-analysis.html)
- [Finnhub kickstarter campaign to raise awareness](https://www.kickstarter.com/projects/finnhub-stock-api/finnhub-free-stock-api-for-investors)
- [Finnhub used by unitersity of South Carolina researchers](http://people.stat.sc.edu/tqdo/realtime-stock-api.html)
- [Finnhub used by unitersity of NYU researchers](https://wp.nyu.edu/finnhub/stock-api-guide/)
