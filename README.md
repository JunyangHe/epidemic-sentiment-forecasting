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
  - SentiFM_Poster.pdf
  - paper.pdf
 

## How to Run
covid_ts_sentiment_preprocessing.ipynb can be run directly with Google Colab after storing [full_data.csv](https://drive.google.com/file/d/1IinOZggf87gCE0866TLAqn0_dXAxKFfi/view?usp=drivesdk), [vaccinations.csv](https://drive.google.com/file/d/1GxojR6cZeRXIz4lLU4-SU6MJuAo6-Q9C/view?usp=drivesdk), [covid-hospitalizations.csv](https://drive.google.com/file/d/1MDn9uFZb1Mqnb3ZmvQzZfnIAsKP2dlUV/view?usp=drivesdk),  [covid-testing-all-observations](https://drive.google.com/file/d/1OT5VEpSxiemaaELfE5Yb3X-pC8CuBT4t/view?usp=drivesdk), and [COVID19_twitter_full_dataset.csv](https://drive.google.com/file/d/1KSi3usKQ8fhaC17n12NBRKCneT0fn5JL/view?usp=drivesdk) in the main Google Drive landing page.


covid_ts_sentiment_forecasting.ipynb can be run directly with Google Colab after storing [covid_us_timeseries.csv](https://drive.google.com/file/d/1iQASvB04Mv_fHvLrCexxv8jHm_WmFBWP/view?usp=drive_link) and [covid_us_sentiment.csv](https://drive.google.com/file/d/1bYhJ2v7esLyN-9XMVKQxtaIOvBRqsUXL/view?usp=drivesdk) in the main Google Drive landing page.

covid_ts_sentiment_forecasting.ipynb can be run directly with Google Colab after storing covid_us_timeseries.csv and covid_ts_sentiment_combined.csv in the main Google Drive landing page.
