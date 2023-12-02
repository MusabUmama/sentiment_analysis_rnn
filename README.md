# sentiment_analysis_rnn

# Sentiment Analysis using Bidirectional RNN Model with Attention Mechanism for Yelp review dataset

This sentiment analysis project utilizes a Bidirectional Recurrent Neural Network (RNN) model equipped with an attention mechanism to perform sentiment analysis on Yelp review data.

# Overview

The project involves:

Data Preprocessing: Cleaning and preparing the Yelp reviews dataset, categorizing sentiments based on star ratings.
Model Architecture: Building a sophisticated neural network using Bidirectional LSTMs and attention layers to understand the context of reviews comprehensively.
Training and Evaluation: Training the model on a subset of data, evaluating its performance on a test set, and analyzing metrics like accuracy, precision, recall, and F1-score.
GitHub Structure: Organized code and files for easy navigation and understanding.

# Usage

Data Preparation: Load the Yelp reviews dataset and preprocess it to extract relevant features like text and star ratings.
Model Building: Design and configure the Bidirectional RNN model with attention layers using TensorFlow and Keras.
Training: Train the model on the preprocessed data and analyze the training/validation metrics to assess model performance.
Evaluation: Evaluate the model's performance on a separate test set to measure its ability to predict sentiments accurately.
Improvement: Experiment with hyperparameters, model architectures, or different embeddings to enhance the model's performance.

# Results

The model achieves an accuracy of around 89% on the test set, demonstrating its capability to distinguish between positive and negative sentiments in Yelp reviews.