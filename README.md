# Sentiment Analysis of Restaurant Reviews

This project aims to perform sentiment analysis on a dataset of restaurant reviews using machine learning techniques. The analysis includes data preprocessing, visualization, model training, and deployment via a Streamlit web application.

## Project Overview

The objective of this project is to classify restaurant reviews as positive or negative based on their sentiment. The key steps involved in this project are:

1. **Data Import and Preprocessing**: Importing the dataset from Kaggle and making it compatible for analysis.
2. **Data Visualization**: Visualizing the data to understand its distribution and key characteristics.
3. **Model Training**: Splitting the data into training and testing sets and training a Multinomial Naive Bayes model.
4. **Model Evaluation**: Evaluating the model’s performance and achieving an accuracy of 81%.
5. **Web Interface**: Using Streamlit to create a web application that takes user input and displays the sentiment prediction.

## Files in the Repository

- `Sentiment Analysis.ipynb`: The Jupyter notebook containing the code for data preprocessing, visualization, model training, and evaluation.
- `restaurant_reviews.tsv`: The dataset containing restaurant reviews used for analysis.
- `result_screenshot.png`: A screenshot showing the results of the sentiment analysis.
- `README.md`: This file, providing an overview and instructions for the project.

## Data Import and Preprocessing

- **Dataset**: The restaurant reviews dataset was sourced from Kaggle.
- **Preprocessing Steps**:
  - Removing punctuation and stopwords
  - Tokenizing the text
  - Vectorizing the text using TF-IDF

## Data Visualization

Visualizations include:
- Distribution of review lengths
- Frequency of positive and negative reviews
- Word clouds for positive and negative reviews

## Model Training and Evaluation

- **Model**: Multinomial Naive Bayes
- **Training**: The dataset was split into training and testing sets using `train_test_split`.
- **Accuracy**: The model achieved an accuracy of 81% on the test set.

## Web Interface

The Streamlit web app provides a simple interface for users to input a restaurant review and receive a sentiment prediction:
- **Input**: Text input for the review.
- **Output**: Sentiment prediction displayed as 1 (positive) or 0 (negative).

## Results

The results of the sentiment analysis, including the accuracy and visualizations, are summarized in the `result_screenshot.png`.

## Conclusion

This project demonstrates the application of machine learning techniques for sentiment analysis of restaurant reviews, providing a functional web application for real-time sentiment prediction.

