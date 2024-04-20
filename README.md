# Sentiment Analysis on Movie Reviews using LSTM, Bi-LSTM, and RNN


<img width="285" alt="Screenshot 2024-03-10 150232" src="https://github.com/shivdattaredekar/Natural-Language-Processing/assets/46707992/847d3b40-8ace-462d-8988-7d4d658e1dd0">

This project focuses on sentiment analysis using Natural Language Processing (NLP) techniques applied to movie reviews data. Three different recurrent neural network (RNN) architectures are explored: Long Short-Term Memory (LSTM), Bidirectional LSTM (Bi-LSTM), and Vanilla RNN.

## Introduction

Sentiment analysis is the task of determining the sentiment or opinion expressed in a piece of text. In this project, we aim to classify the sentiment of movie reviews as positive, negative, or neutral using deep learning models.

## Dataset

The dataset used for this project consists of a large collection of movie reviews, labeled with their corresponding sentiment (positive, negative, or neutral). Each review is preprocessed and tokenized before being fed into the models for training and evaluation.

## Models

Three different RNN architectures are employed for sentiment analysis:

- **LSTM (Long Short-Term Memory)**:
  - LSTM networks are capable of learning long-term dependencies and are well-suited for sequential data like text.
  - They contain memory cells that can maintain information over time, making them effective for tasks like sentiment analysis.

- **Bi-LSTM (Bidirectional Long Short-Term Memory)**:
  - Bi-LSTM networks enhance the LSTM model by processing input sequences in both forward and backward directions.
  - This allows the model to capture contextual information from both past and future states, improving its performance.

- **RNN (Vanilla Recurrent Neural Network)**:
  - Vanilla RNNs are the simplest form of recurrent neural networks.
  - They process input sequences one step at a time, maintaining an internal state that captures information from previous steps.

## Implementation

- Each model is implemented using a deep learning framework such as TensorFlow or PyTorch.
- The models are trained on the movie reviews dataset using appropriate preprocessing techniques.
- We evaluate the performance of each model using metrics such as accuracy, precision, recall, and F1-score on a held-out test set.


## Results
We present the results of our experiments, including accuracy and other relevant metrics, in the "results" directory.

## Conclusion
This project demonstrates the effectiveness of different recurrent neural network architectures for sentiment analysis on movie reviews. By leveraging LSTM, Bi-LSTM, and RNN models, we achieve competitive results in classifying the sentiment of movie reviews.

## Contributors
  - Shivdatta Redekar
  - shivdattaredekar@gmail.com
  - LinkedIn = https://www.linkedin.com/in/shivdatta-redekar-93ab1511a

## License
  - This project is licensed under the MIT License
