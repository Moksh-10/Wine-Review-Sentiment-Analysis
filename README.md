# Wine-Review-Sentiment-Analysis

Description:
This repository contains two models for sentiment analysis on wine reviews using TensorFlow. The models predict whether a wine review reflects high quality (rating of 90 points or higher) or not based on the review descriptions.

Dependencies:
->Python 3.x
->TensorFlow
->TensorFlow Hub
->NumPy
->Pandas
-.Matplotlib

Models:

Model 1 (Neural Network with Pre-trained Embedding):
->Utilizes a pre-trained embedding layer from TensorFlow Hub (https://tfhub.dev/google/nnlm-en-dim50/2).
->Consists of dense layers with dropout for regularization.
->Trained and evaluated on training, validation, and test datasets.

Model 2 (LSTM with Text Vectorization):
->Uses a text vectorization layer for encoding text data.
->Employs an embedding layer followed by LSTM for sequence processing.
->Also includes dense layers with dropout.
->Trained and evaluated on training, validation, and test datasets.

Note:
->The dataset used in this project is the wine reviews dataset (wine-reviews.csv).
->Model 1 utilizes a pre-trained embedding layer for word representations, while Model 2 uses text vectorization and LSTM for sequence processing.
