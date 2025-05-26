# Stock Day Trading with PyTorch and LSTM networks

![image](https://github.com/user-attachments/assets/d6bd51c3-9084-4062-8c4c-c5d77c2f14a2)

This project implements a deep learning model using Long Short-Term Memory (LSTM) networks in PyTorch to classify daily stock price direction (up/down) for stocks in the S&P 500 index. Using historical stock price and volume data sourced via the `yfinance` API, the model incorporates engineered technical indicators and focuses on predicting directional movement instead of raw prices to maintain data stationarity. 

Model performance is benchmarked against both a perfect foresight strategy and a random trading strategy to evaluate the model's predictive value. The project also explores model scalability across the full index and discusses challenges in applying such models in real-world trading.

## References
- Jin Choi, PhD. (2023, September 18). *Using LSTMs to Predict Stock Prices* [Video]. YouTube. [Source](https://www.youtube.com/watch?v=Vbj2Zzwg8jc)
- ritvikmath. (2023, April 11). *I Day Traded \$1000 of Stocks using the LSTM Model* [Video]. YouTube. [Source](https://www.youtube.com/watch?v=-uqNYTUTqdc)
- ritvikmath. (2023, April 18). *I Beat the Market Using LSTM to Trade \$1000 of Stocks ... kind of* [Video]. YouTube. [Source](https://www.youtube.com/watch?v=s0CrdcwUZTs)
