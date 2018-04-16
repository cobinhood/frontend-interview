Create a COBINHOOD market monitor app from [public APIs](https://cobinhood.github.io/api-public/).

## Environment
The app should be able to run on the latest Chrome browser.

## Requirements
The app should contain at least two pages:
1. **Pair List**  
A list of all available trading pairs, grouped by their `base` currency  
Reference: [Trading Pairs API](https://cobinhood.github.io/api-public/#get-all-trading-pairs)
> If a trading pair has ID `COB-ETH`, then `COB` is its `base` currency and `ETH` is its `quote` currency.

2. **Trading Pair Page**  
Details of a trading pair, including `last price`, `24hr high`, `24hr low`, `24hr volume`, `highest bid` and `lowest ask`  
Reference: [Tickers API](https://cobinhood.github.io/api-public/#get-ticker)

## Optional Features
- Client side navigation
- Use [WebSocket](https://cobinhood.github.io/api-public/#ticker-2) instead of RESTful APIs for ticker price
- Draw candle chart in trading pair page. Reference: [Candles API](https://cobinhood.github.io/api-public/#get-candles)
- Responsive layout

## Notes
Life is short. There are other important things to do. Please **DO NOT** spend more than **1 day** on this assignment.
