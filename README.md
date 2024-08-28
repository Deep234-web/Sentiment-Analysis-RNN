# Sentiment Analysis RNN

This project is a simple web application built using Streamlit that allows users to classify the sentiment of IMDB movie reviews as either **positive** or **negative**. It utilizes a pre-trained Recurrent Neural Network (RNN) model with ReLU activation, trained on the IMDB dataset, to predict the sentiment of the provided movie reviews.

## Features

- **User-Friendly Interface**: An intuitive web interface that enables users to input movie reviews and receive instant sentiment analysis.
- **Pre-trained Model**: The model used in this application is trained on the IMDB dataset, which contains 50,000 movie reviews, making it robust in determining the sentiment.
- **Prediction Score**: Along with the sentiment (positive/negative), the app also provides a prediction score that indicates the confidence of the model's prediction.

## How It Works

1. **User Input**: Users can enter their movie review in the provided text area.
2. **Preprocessing**: The input review is preprocessed to match the format expected by the model. This includes tokenizing the text and padding sequences.
3. **Prediction**: The preprocessed review is fed into the RNN model, which predicts the sentiment of the review.
4. **Output**: The sentiment (positive/negative) and the prediction score are displayed to the user.

## Live Demo

Try out the live demo of the IMDB Movie Review Sentiment Analysis app [here](https://sentiment-analysis-rnn-yhcbvktgappers7bhdsgnjd.streamlit.app/).

