# COVINDIA : Deep Learning Model for Sentiment Classification on COVID19 Tweets from India

## Overview
Various variations of deep learning model to perform sentiment analysis on tweets related to COVID19 from India

## Datasets
1. Tweet dataset : [Kaggle dataset](https://www.kaggle.com/surajkum1198/twitterdata)
2. GloVe embeddings : [GloVe](https://www.kaggle.com/rtatman/glove-global-vectors-for-word-representation)
3. FastText embeddings : [FastText](https://www.kaggle.com/vsmolyakov/fasttext)
4. GloVe Twitter : [GloveTwitter](https://www.kaggle.com/bertcarremans/glovetwitter27b100dtxt)


| Model Description                              | Training Accuracy |
|------------------------------------------------|-------------------|
| Basic LSTM                                     |                   |
| LSTM + GloVe Embeddings                        |                   |
| LSTM + FastText Embeddings                     |                   |
| LSTM + GloVe Twitter Embeddings                |                   |
| Basic Bi-directional LSTM                      |                   |
| Bi-directional LSTM + GloVe Embeddings         |                   |
| Bi-directional LSTM + FastText Embeddings      |                   |
| Bi-directional LSTM + GloVe Twitter Embeddings |92.2%               |
| BERT                                           |                   |
| GRU                                            |                   |
