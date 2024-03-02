# Final Capstone

This project involves the sentiment analysis of Amazon listing reviews for a mix of products ranging from a Tablet to some batteries. The analysis is performed using Natural Language Processing (NLP) techniques, primarily leveraging the TextBlob library and user-defined functions. The reviews are sourced from a CSV file obtained from Kaggle, and the data manipulation is carried out using dataframes in the pandas library.

The model utilises TextBlob library to rate the reviews on a scale from 1 (positive) to -1 (negative). This quantitative approach aids in categorising and assessing qualitative data, providing valuable insights for businesses to gauge general customer satisfaction with their products.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Acknowledgements](#acknowledgements)

## Features {#features}

* **Data Source:** Reviews are loaded from a CSV file obtained from Kaggle, using the pandas library.
* **Sentiment Analysis:** The model rates the sentiment of a given review on a scale from -1 (negative) to 1 (positive).
* **Preprocessing:** Reviews undergo preprocessing, including converting to lowercase and removing stop words, to enhance the accuracy of sentiment analysis.

## Prerequisites {#prerequisites}

Before running the model, ensure you have the following dependencies installed:

* Python 3.x
* spaCy
* TextBlob
* pandas

**Install dependencies using the following command in your terminal:**

pip install spacy textblob pandas

**Download spaCy models:**

python -m spacy download en_core_web_sm

python -m spacy download en_core_web_md


## Installation {#installation}

Clone the repository using the following command:

git clone https://github.com/your-username/sentiment-analysis-model.git


## Acknowledgements {#acknowledgements}

The dataset used in this project was obtained from [Kaggle: Amazon Product Reviews](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products).
