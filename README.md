**Fake News Detection Using LSTM**

This project aims to classify news articles as real or fake using Natural Language Processing (NLP) techniques and a Long Short-Term Memory (LSTM) neural network. The dataset used for this project is taken from Kaggle’s Fake News Detection Challenge. The goal is to build a binary text classifier that accurately predicts whether a given news article is fake or real based on its content.
Link of the dataset: https://www.kaggle.com/code/simtoor/fake-news-detection/input?select=train.csv

**Model Architecture**

We use a Recurrent Neural Network (RNN) variant — LSTM (Long Short-Term Memory) — which is well-suited for sequential data like text.

Steps:
1. Text Cleaning:
  -> Removal of punctuations, stopwords, HTML tags, etc. Also applied Tokenization and convert all words to lowercase

2. Embedding:
  -> Use of an Embedding Layer to convert words into dense vectors

3. LSTM Layer:
  -> Captures long-term dependencies in the text

4. Dense Output Layer:
  -> Applies a sigmoid activation to produce binary output (fake or real)
