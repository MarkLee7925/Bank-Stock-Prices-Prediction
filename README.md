# Bank-Stock-Prices-Prediction

The objective of this project is to predict the (closing) stock market prices of each of the "Big Five Banks" in Canada over a time period of over five years. These banks include:

- Bank of Montreal (BMO)
- Canadian Imperial Bank of Commerce (CIBC)
- Royal Bank of Canada (RBC)
- Bank of Nova Scotia (BNS, Scotiabank)
- Toronto Dominion Bank (TD Bank)

## Datasets:

All .csv data files for each model were retrieved from Yahoo Finance (see References) and can be located in the "data" folder.

## Models:

The stock market trends were predicted using Long Short-Term Memory (LSTM) models. Although the trends were captured over a five year time frame, this can be scaled to even longer periods.

Due to the highly unpredictable nature of stock markets, the performances of each model varies over time. Thus, the intention was to predict (as closely as possible) the overall trends of the stock prices rather than the actual values themselves. In other words, each model was designed to determine if the stock  prices were increasing or decreasing over time.

## DISCLAIMER:

This project is for illustration purposes ONLY! It was never meant to be used for any financial consulation or advice in any way. Please consult your local financial advisor for any advice or concerns.

## References:

- BMO: https://finance.yahoo.com/quote/BMO.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- CIBC: https://finance.yahoo.com/quote/CM-PQ.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- RBC: https://finance.yahoo.com/quote/RY.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- Scotiabank: https://finance.yahoo.com/quote/BNS.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- TD Bank: https://finance.yahoo.com/quote/TD.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
