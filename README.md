# Emotion Intensity Analysis in Text

## Overview

This project aims to analyze the intensity of emotions in text using various models and techniques. We explore the use of statistical models, lexicon-based approaches, and deep learning models to predict the intensity of four emotions (anger, fear, joy, sadness) in text data.

## Data

We use a dataset containing tweets labeled with the intensity of four emotions: anger, fear, joy, and sadness. The dataset is split into training, validation, and test sets for model development and evaluation.
Models

    VADER: A rule-based sentiment analysis tool used to assign sentiment scores to text.
    Lexicon-based Approach: Utilizes the NRC Emotion Lexicon to assign emotion labels and scores to text.
    Linear Regression: A statistical model used to predict emotion intensity based on text features.
    LSTM: A deep learning model that uses a Long Short-Term Memory network to predict emotion intensity from text sequences.

## Results

    VADER: RMSE on Test Set: 0.757
    Lexicon-based Approach: Accuracy: 0.423
    Linear Regression:
        Anger: RMSE on Test Set: 0.235
        Fear: RMSE on Test Set: 0.210
        Joy: RMSE on Test Set: 0.227
        Sadness: RMSE on Test Set: 0.270
    LSTM: Test Loss: 0.004
