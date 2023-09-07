# NLP Sentiment Analysis

Perform sentiment analysis on text data using Natural Language Processing (NLP) techniques. This project includes data preprocessing, feature extraction, and a trained model for sentiment classification.

## Overview

Sentiment analysis, also known as opinion mining, involves determining the sentiment or emotion expressed in a piece of text. This project aims to provide a basic framework for performing sentiment analysis using NLP.

## NLP Process

While working on any NLP problem, the following steps are typically involved:

1. **Dataset Acquisition**: Obtain a textual dataset relevant to the problem at hand.

2. **Data Preprocessing**:
   - **Tokenization**: Break down text into individual words or tokens.
   - **Stopwords Removal**: Eliminate common words (e.g., "and", "the") that do not contribute much information.
   - **Stemming**: Reduce words to their base or root form (e.g., "running" becomes "run").

3. **Text Vectorization**:
   - Convert the preprocessed text into numerical form for machine learning models to process.

4. **Model Training and Evaluation**:
   - Train a machine learning model (in this project, a Passive Aggressive Classifier is used) on the vectorized text data.
   - Evaluate the model's performance using appropriate metrics.

5. **User Input and Prediction**:
   - Allow users to input text for sentiment analysis using the trained model.

## Features

- Data cleaning and preprocessing for text analysis
- Word cloud generation for visualizing most common words
- Utilizes a Passive Aggressive Classifier for sentiment classification
- Interactive user input for testing the sentiment analysis model

## Usage

1. Clone this repository to your local machine.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the Python script using a Jupyter Notebook or Python file.
4. Follow the prompts to input text for sentiment analysis.

## Dependencies

- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- wordcloud

## Dataset

The dataset used in this project is sourced from [IMDb Dataset](https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).
