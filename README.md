

# Sentiment Analysis with LSTM

## Overview

This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.

## Prerequisites

Before running the code, make sure you have the following prerequisites installed:

- Python 3
- TensorFlow
- Pandas
- Numpy
- Matplotlib
- Seaborn
- NLTK
- scikit-learn
- Jupyter Notebook (optional)

You can install the required Python packages using `pip`. For example:
pip install tensorflow pandas numpy matplotlib seaborn nltk scikit-learn

## Project Structure

The project directory is structured as follows:
- README.md # This README file
- sentiment_analysis.ipynb # Jupyter Notebook with code
- training.1600000.processed.noemoticon.csv # Twitter dataset

## Dataset

We use the `training.1600000.processed.noemoticon.csv` dataset, which contains labeled tweets. The dataset is divided into positive (4) and negative (0) sentiments.
https://www.kaggle.com/datasets/kazanova/sentiment140

##Model Training

We train an LSTM model for sentiment analysis using the Twitter data. The model architecture includes an embedding layer, bidirectional LSTM layers, and fully connected layers. The model is trained and evaluated using training, validation, and testing datasets.

## Results
The model achieves an accuracy of approximately 74.15% on the test dataset. However, it's essential to consider potential overfitting and explore hyperparameter tuning to improve performance further.

## Acknowledgments

The dataset used in this project is from Twitter Sentiment140 dataset.
Inspired by sentiment analysis tutorials and resources from TensorFlow and NLTK.




