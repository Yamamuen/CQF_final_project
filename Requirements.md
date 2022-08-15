# DL assignment Requirements

* LSTM classification on up/down moves

* Features + feature engineering: financial rations/adv technical indicators/volatility estimators (lookback 5/10/21/50D). Such as:

    * EMA, Volatility, ATR.

    * Technical indicators, such as RSI, Stochastic K, MACD, CCI, ATR, Acc/Dist., Bollinger Bands (varying lookback).

    * Volume info appears to be immediate-term signals, while we aim for prediction.

    * drift-independent volatility w/ overnight jump (Yang & Zhang 2000).

    * empirical work might find that RNNs/Reinforcement Learning might work better WITHOUT past returns!

* Feature Scaling.

* EDA on features (features map, SOM, DTR for feature selection). May need to reduce dimensionality. Correlation maps and scatterplots work as well.

* Target: return DIRECTION prediction (up/down moves).

