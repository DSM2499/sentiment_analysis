# Sentiment Analysis with LSTM

## Overview
This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.

## Features
- Sentiment classification using LSTM
- Data preprocessing and visualization
- Model training and evaluation

## Prerequisites
Before running the code, ensure you have the following prerequisites installed:
- Python 3
- TensorFlow
- Pandas
- Numpy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Jupyter Notebook (optional)

Install the required packages using:

pip install tensorflow pandas numpy matplotlib seaborn nltk scikit-learn

## Installation

1. Clone the repository:

   git clone https://github.com/DSM2499/sentiment_analysis.git

2. Navigate to the project Directory:

   cd sentiment_analysis

## Usage

Run the Jupyter Notebook to see the complete workflow:

jupyter notebook sentiment_analysis.ipynb

## Project Structure

* README.md: This README file
* sentiment_analysis.ipynb: Jupyter Notebook with code
* training.1600000.processed.noemoticon.csv: Twitter dataset

### Dataset

We use the Sentiment140 dataset containing labeled tweets. The dataset includes both positive (4) and negative (0) sentiments.

### Model Training

The LSTM model includes an embedding layer, bidirectional LSTM layers, and fully connected layers. The model is trained and evaluated using training, validation, and test datasets.

## Contact

For questions or support, please contact me at dinakardsm@gmail.com
