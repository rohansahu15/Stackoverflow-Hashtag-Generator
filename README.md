# StackOverflow Hashtag Generator

This project generates relevant hashtags for StackOverflow questions using Natural Language Processing (NLP) techniques. Various machine learning models were explored, and Support Vector Machine (SVM) was selected as it provided the best results.

## Features
- **NLP Preprocessing**: Includes tokenization, stopword removal, lemmatization, and vectorization.
- **Machine Learning Models**: Several models were tested, including:
  - Support Vector Machine (SVM)
  - Logistic Regression
  - Multilayer Perceptron (MLP)
  - Multinomial Naive Bayes (MultinomialNB)
- **Hashtag Prediction**: The system predicts relevant hashtags for a given StackOverflow question based on its content.

## Project Structure
- `data/`: Contains the dataset used for training and testing.
- `preprocessing.py`: Script for text preprocessing steps such as tokenization, stopword removal, and lemmatization.
- `models.py`: Contains different machine learning models including SVM, logistic regression, MLP, and MultinomialNB.
- `train.py`: Training script where different models are trained and evaluated.
- `app.py`: A simple web interface to input StackOverflow questions and get relevant hashtag predictions.
- `README.md`: Project documentation.


## Model Selection

In this project, several machine learning models were evaluated to determine the best approach for predicting relevant hashtags from StackOverflow questions. The models tested were:

- **Support Vector Machine (SVM)**: This model provided the best performance in terms of accuracy and efficiency. It was selected as the final model for hashtag prediction.
- **Logistic Regression**: This model performed decently but did not surpass SVM in accuracy.
- **Multilayer Perceptron (MLP)**: A neural network model that required more computational resources and time to train but did not show significant improvement over SVM.
- **Multinomial Naive Bayes (MultinomialNB)**: This model was computationally faster but less accurate compared to the other models.

After many experimentation, **SVM** was chosen as the best-performing model for this project.

