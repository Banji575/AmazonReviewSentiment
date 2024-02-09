# AmazonReviewSentiment
AmazonReviewSentiment is a machine learning project that uses NLP and Logistic Regression to classify Amazon product reviews into positive or negative sentiments, providing key insights into customer feedback.

This repository contains the code and methodology for a machine learning project focused on sentiment analysis of Amazon product reviews. The project aims to classify reviews into positive or negative sentiment using Logistic Regression, a popular algorithm in natural language processing and text classification tasks.

## Project Overview

Sentiment analysis of Amazon reviews is crucial for understanding customer satisfaction and improving product quality. This project leverages Python, pandas for data manipulation, NLTK for natural language processing, and scikit-learn for machine learning tasks.

## Features

- **Data Preprocessing**: Cleaning and preparing text data for machine learning, including removing stopwords and punctuation.
- **Vectorization**: Transforming text into numerical data using TF-IDF vectorization.
- **Model Training**: Utilizing Logistic Regression to classify reviews into positive or negative sentiment.
- **Model Evaluation**: Assessing the model's performance using accuracy, precision, recall, and F1 score.
- **Hyperparameter Tuning**: Optimizing the Logistic Regression model using GridSearchCV to find the best hyperparameters.

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

This project requires Python 3.6+ and the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- NLTK

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn nltk
```
### Installation
Clone the repo:

```bash
git clone https://github.com/Banji575/AmazonReviewSentiment.git
```

### Usage
To run the sentiment analysis:

- Prepare your dataset.
- Run the preprocessing script to clean the data.
- Use the training script to train the Logistic Regression model.
- Evaluate the model performance with the provided evaluation script.

### Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.


