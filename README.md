# Bank-Stock-Prices-Prediction

The objective of this project is to predict the stock market prices of each of the "Big Five Banks" in Canada over a time period of five years. These banks include:

- Bank of Montreal (BMO)
- Canadian Imperial Bank of Commerce (CIBC)
- Royal Bank of Canada (RBC)
- Bank of Nova Scotia (Scotiabank)
- Toronto Dominion Bank (TD Bank)

## Datasets:

All .csv data files for each model were retrieved from Yahoo Finance (see References) and can be located in the "data" folder.

## Models:

The stock market trends were predicted using Long Short-Term Memory (LSTM) models. Each model contains multiple layers with Dropout regularization to reduce the likelihood of overfitting (model performs adequately in training, but poorly in testing/validation). Although the model captured the trends over a five year time frame, this can be scaled to even longer periods.

Due to the highly unpredictable nature of stock markets, the performances of each model varies over time. Thus, the intention was to predict (as closely as possible) the overall trends of the stock prices rather than the actual values themselves. In other words, each model was designed to determine if the stock  prices were increasing or decreasing over time.

## References:

- BMO: https://finance.yahoo.com/quote/BMO.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- CIBC: https://finance.yahoo.com/quote/CM-PQ.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- RBC: https://finance.yahoo.com/quote/RY.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- Scotiabank: https://finance.yahoo.com/quote/BNS.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- TD Bank: https://finance.yahoo.com/quote/TD.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
