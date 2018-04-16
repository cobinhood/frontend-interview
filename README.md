## COBINHOOD front-end pre-interview assignment
Create a COBINHOOD price monitor app from [public APIs](https://cobinhood.github.io/api-public/).

## Runtime Environment
latest Chrome browser.

## Requirements
The app should contain the following two pages:
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
- *Anything* that makes it a better price monitor app

## Submission
Please submit a ZIP/Tarball file containing `index.html` and other required JS, CSS... files.  
- If your HTML, JS or CSS files are bundled or transformed with tools like `webpack`, `babel`... etc, include your original sources in `/src` folder.
- If your submission contains server side logic, include a README.md for setting up the server side environment

The structure of the submitted file should be like:
```bash
/app/index.html #entrance of the web app
/app/*.js #JavaScript file used by the app
/app/*.css #Style sheet used by the app

/src/**/*.* #source files

README.md #guide on how to set up the server side environment 
```

## Notes
1. Life is short. There are other important things to do. Please **DO NOT** spend more than **1 day** on this assignment.
2. The code should be in **production** quality. Performance and code style should be considered.
3. Feel free to use any language or framework.
