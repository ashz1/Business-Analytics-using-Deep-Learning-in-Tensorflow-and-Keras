# Business-Analytics-using-Deep-Learning-in-Tensorflow-and-Keras
# Lending Club Loan Prediction with Deep Learning

## Project Overview

This project involves predicting the status of Lending Club loans using a Deep Learning model built with TensorFlow and Keras. The dataset includes loan information from 2007 to 2015, including loan status and payment details, with additional features such as credit scores and address details.

## Objective

The goal is to classify loan statuses into three categories: Good, Warning, and Bad.

## Dataset

- **Source:** Lending Club Loan Data on Kaggle
- **Size:** ~890,000 observations and 75 variables
- **Features:** Includes loan amount, interest rate, credit score, and more.

## Methodology

1. **Data Preparation:**
   - Cleaned and preprocessed the data
   - Dropped irrelevant and high-missing-value columns
   - Encoded categorical variables using one-hot encoding

2. **Model:**
   - Built a 2-layer fully connected neural network
   - Used Batch Normalization and ADAM optimizer
   - Applied ReLU activation in hidden layers and Softmax in the output layer

3. **Evaluation:**
   - Achieved an accuracy of 96.5% on test data
   - The model shows low bias and variance, with no signs of overfitting

## Conclusion

The model demonstrates strong performance and accuracy in predicting loan statuses. Future improvements could include implementing binary classification and exploring regularization techniques.

## Installation

Make sure to install the required libraries:

```bash
pip install numpy pandas seaborn matplotlib tensorflow keras scikit-learn
