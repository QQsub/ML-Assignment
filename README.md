# Fake News Detection

This project focuses on detecting fake news using both deep learning and traditional machine learning approaches. The goal is to classify news articles as either fake or real based on their content.

## Method
- **Deep Learning Approach:**
  - Implemented a Bidirectional LSTM (BiLSTM) model.
  - Used word embeddings for semantic representation of text.
  - Achieved over 99% accuracy on both training and test sets.

- **Classic Machine Learning Approach:**
  - Implemented a Logistic Regression model.
  - Used Count Vectorization for feature extraction.
  - Achieved competitive results with a simpler architecture.

## Results
- **Bidirectional LSTM:**
  - Training Accuracy: 99.86%
  - Test Accuracy: 99.88%

- **Logistic Regression:**
  - Achieved 96% accuracy with Count Vectorized features, demonstrating the effectiveness of simpler models in binary classification tasks.

This project demonstrates the effectiveness of deep learning models like BiLSTM for text classification tasks, while also comparing them with classic machine learning approaches like Logistic Regression.
