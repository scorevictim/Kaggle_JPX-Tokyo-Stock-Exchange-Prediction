![](https://storage.googleapis.com/kaggle-competitions/kaggle/34349/logos/header.png?t=2022-03-09-00-33-57)

# JPX Tokyo Stock Exchange Prediction

## About

This work is for a Kaggle competition: JPX Tokyo Stock Exchange Prediction

Japan Exchange Group, Inc. (JPX) is a holding company operating one of the largest stock exchanges in the world, Tokyo Stock Exchange (TSE), and derivatives exchanges Osaka Exchange (OSE) and Tokyo Commodity Exchange (TOCOM). JPX is hosting this competition and is supported by AI technology company AlpacaJapan Co.,Ltd.

This competition will compare your models against real future returns after the training phase is complete. The competition will involve building portfolios from the stocks eligible for predictions (around 2,000 stocks). Specifically, each participant ranks the stocks from highest to lowest expected returns and is evaluated on the difference in returns between the top and bottom 200 stocks. You'll have access to financial data from the Japanese market, such as stock information and historical stock prices to train and test your model.

Link for this competition: <https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction>

Data used in this project: <https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction/data>

## Content

- Exploratory Data Analysis & Data Clean

- Feature Engineering

- Model Building

- Prediction Export

## Dependencies

This work is based on Python 3.9

See all the needed libraries in "requirements.txt"

To run most parts of the code locally, you can use "pip install -r requirements.txt" to replicate the environment. Make sure to new a python virtual environments to avoid conflicts.

For the "Prediction Export" part, however, you need to use Kaggle notebook since it uses an Kaggle API. Thus, the recommended way of running the code is to upload the jupyter notebook to Kaggle.
