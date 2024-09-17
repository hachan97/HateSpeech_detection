# Hate Speech and Offensive Language Dataset Analysis

This project demonstrates how to analyze and classify Hate Speech and Offensive Language dataset from Kaggle using a Jupyter Notebook.

## Project Overview
This project downloads the dataset from Kaggle, extract it, and perform basic data analysis using pandas. The dataset contains labeled data for hate speech and offensive language, which can be used for various natural language processing tasks.

## Preprocessing Steps
In this notebook, I performed two different preprocessing steps on the dataset:

### 1. Text Cleaning
The first preprocessing step involved cleaning the text data. This included:
- Removing special characters and punctuation.
- Converting all text to lowercase.
- Removing stop words (common words that do not contribute much to the meaning of the text).
### 2. Tokenization
The second preprocessing step involved tokenizing, removing Stopwords and Lementization of the cleaned text data.

**Requirements**
- Python 3.x
- Jupyter Notebook
- pandas
- nltk
- Kaggle API

## Classification 
This project trained a few Supervised Classifier, namely: MultinomialNB Model, Logistic Model, and a Random Forest model.

## Acknowledgements
The [dataset](https://www.kaggle.com/datasets/mrmorj/hate-speech-and-offensive-language-dataset?resource=download) used in this project is provided by [mrmorj](https://www.kaggle.com/mrmorj) on Kaggle.
Thanks to Kaggle for providing the platform and API to access datasets.
