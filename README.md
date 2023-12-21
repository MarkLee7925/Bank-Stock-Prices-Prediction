# Bank-Stock-Prices-Prediction

The main objective of this project is to predict the (closing) stock market prices of each of the "Big Five" Banks in Canada for the next 7 days using historical data collected over a (scalable) period of 8+ years. These banks include:

- Bank of Montreal (BMO)
- Canadian Imperial Bank of Commerce (CIBC)
- Royal Bank of Canada (RBC)
- Bank of Nova Scotia (BNS, Scotiabank)
- Toronto Dominion Bank (TD Bank)

## Datasets:

All .csv data files for each model were retrieved from Yahoo Finance (see References) and can be located in the "data" folder. All stock price values are in Canadian Dollars (CAD$).

![BankStockPred](https://github.com/MarkLee7925/Bank-Stock-Prices-Prediction/assets/59748085/11d29d7e-1209-4c87-89a9-6cccade446c6)
*created using Power BI.

## Models:

The stock market trends were predicted using Long Short-Term Memory (LSTM) models, a type of Recurrent Neural Network (RNN) which predicts future values based on feedback gathered from previous data trends. Although the trends were captured over an 8-year period, these can be modified as per user preferences. To predict the stock price trends over the next 7 days, the rolling (mean) averages were computed and added to the current datasets used for prediction.

Due to the highly unpredictable nature of stock markets, the performances of each model will vary over time. Thus, the intention was to predict (as closely as possible) the overall trends of the stock prices rather than the actual values themselves. In other words, each model was designed to determine if the stock prices were increasing or decreasing over time.

## DISCLAIMER:

This project is for illustration purposes only! Any results shown should never be used for financial consultation or guidance whatsoever. Please consult your local financial advisor for any advice or concerns.

## References:

- BMO: https://finance.yahoo.com/quote/BMO.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- CIBC: https://finance.yahoo.com/quote/CM-PQ.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- RBC: https://finance.yahoo.com/quote/RY.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- Scotiabank: https://finance.yahoo.com/quote/BNS.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- TD Bank: https://finance.yahoo.com/quote/TD.TO/history?period1=1426118400&period2=1675987200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
