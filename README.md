# Bank-Stock-Prices-Regression

The purpose of this project is to predict the stock market prices of each of the "Five Banks" across Canada. These banks include:

- Bank of Montreal (BMO)
- Canadian Imperial Bank of Commerce (CIBC)
- Royal Bank of Canada (RBC)
- Bank of Nova Scotia (Scotiabank)
- Toronto Dominion Bank (TD Bank)

## Dataset:

The data files for each model were retrieved from Yahoo finance (see References). All .csv files can be found in the "data" folder. Although the data presented a five-year period, each model can also work for longer periods.

## Models:

The stock market trends were predicted using Long Short-Term Memory (LSTM) models. Each model contains multiple layers with Dropout regularization. 

## References:

- BMO: https://finance.yahoo.com/quote/BMO.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- CIBC: https://finance.yahoo.com/quote/CM-PQ.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- RBC: https://finance.yahoo.com/quote/RY.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- Scotiabank: https://finance.yahoo.com/quote/BNS.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true
- TD Bank: https://finance.yahoo.com/quote/TD.TO/history?period1=1473724800&period2=1631491200&interval=1d&filter=history&frequency=1d&includeAdjustedClose=true

