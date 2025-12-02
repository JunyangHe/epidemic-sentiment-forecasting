# SentiFM — Epidemic Forecasting with Text Sentiment Analyses

[Project website](https://yulewang97.github.io/SentiLLM-Webpage/)

SentiFM is a research codebase for combining epidemiological time-series models with sentiment extracted from text (social media, news, etc.) to improve short-term epidemic forecasts.

- doc/ — poster and paper PDFs

Project structure
- README.md
- src/
  - covid_ts_sentiment_preprocessing.ipynb               # preprocessing pipelines (cleaning, feature engineering)
  - covid_ts_sentiment_forecasting.ipynb                 # naive concatenation with LSTM + Chronos2 training & inference
  - 8803_EPI_llama_lstm_multimodel_fusion.ipynb          # SARIMAX modeling + LLaMA 3 + multi-model fusion
- data/
  - raw/
  - processed/
- doc/
  - poster.pdf
  - paper.pdf
