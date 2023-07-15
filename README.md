# Fake News Classification

This repository contains a Jupyter Notebook that performs fake news classification using a RandomForestClassifier. The Notebook utilizes various libraries and techniques to preprocess the data, train the model, and make predictions.

## Introduction

Fake news has become a significant issue in today's information age. This Notebook aims to address this problem by classifying news articles as either true or fake using a RandomForestClassifier model. The code employs natural language processing techniques and machine learning algorithms to analyze and classify news data.

## Installation

To run the code, follow these steps:

1. Clone this repository:

```
   git clone https://github.com/yourusername/fake-news-classification.git
```

2. Open the Jupyter Notebook:

```
   jupyter notebook fakeNews.ipynb
```

3. Execute the code cells in sequential order.

## Usage

Follow the instructions in the Notebook to enter the news title and article. The code will predict whether the news is classified as true or fake.

## Data

The Notebook downloads a dataset containing true and fake news from a provided URL. The dataset consists of CSV files: `True.csv` and `Fake.csv`. The files are stored in a directory named `data2`.

## Preprocessing

Before training the model, the data is preprocessed to clean the text. The preprocessing steps include removing links, special symbols, non-word characters, numbers, and stopwords. The cleaned text is stored in a new column named `text`.

## Model Training

The data is split into training and testing sets. The text data is transformed into feature vectors using the TfidfVectorizer. The RandomForestClassifier model is then initialized and trained using the training set.

## Model Evaluation

The accuracy of the model is calculated and printed to evaluate its performance. Additionally, a confusion matrix is generated to provide insights into the classification results.

## Prediction

Users can input news title and article to make predictions using the trained model. The input is preprocessed and vectorized, and the model predicts whether the news is classified as true or fake.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please submit a pull request or open an issue.
