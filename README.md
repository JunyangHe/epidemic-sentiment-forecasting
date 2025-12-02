# SentiFM — Epidemic Forecasting with Text Sentiment Analyses

[Project website](https://yulewang97.github.io/SentiLLM-Webpage/)

SentiFM is a research codebase for combining epidemiological time-series models with sentiment extracted from text (social media, news, etc.) to improve short-term epidemic forecasts.

## Project structure
- README.md
- src/
  - covid_ts_sentiment_preprocessing.ipynb               (preprocessing pipelines, cleaning, feature engineering)
  - covid_ts_sentiment_forecasting.ipynb                 (naive concatenation with LSTM + Chronos2 training & inference)
- 8803_EPI_llama_lstm_multimodel_fusion.ipynb          (SARIMAX modeling + LLaMA 3 + multi-model fusion)
- doc/
  - poster.pdf
  - paper.pdf
 

## How to Run

covid_ts_sentiment_forecasting.ipynb can be run directly with Google Colab after storing [covid_us_timeseries.csv](https://drive.google.com/file/d/1og5q0-X4APqxqGzIJhM2IuEleFIlONTm/view?usp=drivesdk) and [covid_us_sentiment.csv](https://drive.google.com/file/d/1bYhJ2v7esLyN-9XMVKQxtaIOvBRqsUXL/view?usp=drivesdk) in the main Google Drive landing page.
