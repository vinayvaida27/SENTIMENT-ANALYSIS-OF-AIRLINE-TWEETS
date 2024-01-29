# Airline Tweets Sentiment Analysis

Welcome to the GitHub repository for our sentiment analysis project! This project is designed to classify sentiments in tweets related to airlines into three categories: negative, neutral, and positive. The repository includes a dataset of augmented tweets, serialized machine learning models, and a Jupyter notebook containing the project's code.

## Repository Contents

- `augmented_tweets_final.csv` - The augmented dataset used for training and evaluating the models.
- `stacking_ensemble_model.pkl` - The serialized Stacking Ensemble model, which is our final, best-performing model.
- `tfidf_vectorizer_final.pkl` - The serialized TfidfVectorizer used for transforming text data into feature vectors.
- `team-8-machine_learning-Finalcode.ipynb` - A comprehensive Jupyter notebook with all the code for preprocessing, model training, hyperparameter tuning, evaluation, and predictions.
- `testing_model.ipynb` - A notebook for loading the serialized models and performing test predictions to evaluate model performance.

## Project Overview

The project utilizes a variety of machine learning models and ultimately selects a Stacking Ensemble model for its superior performance in accurately classifying tweet sentiments. The models are trained on an augmented dataset that ensures a balanced representation of sentiments, which is crucial for unbiased machine learning predictions.

## Getting Started

To get started with this project:

1. Clone the repository to your local machine.
2. Install Python and the necessary libraries (the list of which can be extracted from the import statements in the Jupyter notebooks).
3. Run `team-8-machine_learning-Finalcode.ipynb` to view the project's development process or `testing_model.ipynb` to test the models' performance on new data.

## Model Deployment

The Stacking Ensemble model (`stacking_ensemble_model.pkl`) is the final model chosen due to its high accuracy and robustness. The model, along with the `tfidf_vectorizer_final.pkl`, can be deployed for sentiment analysis tasks.


