# Ethereum Price Direction Using Reddit Data

This project utilizes machine learning and natural language processing techniques to predict Ethereum's price direction using data collected from Reddit.

## Data Sources

Comments were collected from specific subreddits using the Reddit API.

Hourly Ethereum price data was retrieved from Binance API, starting from 2017.

## Models Used

The following language models were used to perform sentiment analysis on Reddit comments:

XLM (Cross-lingual Model)

DistilBERT

ALBERT

BERT

These models were trained for sentiment analysis, and their results were integrated with Ethereum price data to predict price direction.

## Technologies Used

Python

TensorFlow / PyTorch

spaCy

Binance API

Reddit API (PRAW)

Google Colab 

## Results and Visualization

Sentiment analysis results were compared with Ethereum price movements and presented using various visualizations.

Model performance was evaluated using precision, recall, F1-score, and AUC-ROC metrics.
