# Sentiment Analysis of IMDb Reviews
# Overview
This project focuses on performing sentiment analysis on IMDb movie reviews. The goal is to build and evaluate neural network models that can accurately predict the sentiment (positive or negative) expressed in movie reviews. The project encompasses comprehensive text preprocessing followed by the construction of different neural network models.

# Project Structure
Jupyter notebook containing the entire project workflow including data preprocessing, model building, and evaluation.

# Data Preprocessing
The preprocessing of the IMDb movie reviews involves several steps to convert raw text data into a format suitable for neural network models:

Remove HTML Tags: Stripping HTML tags from the reviews using BeautifulSoup.
Convert to Lowercase: Standardizing the text by converting all characters to lowercase.
Remove Punctuation and Special Characters: Eliminating unnecessary punctuation and special characters, with the option to retain sentiment-relevant punctuation like exclamation marks.
Tokenization: Breaking down each review into individual words using NLTK's word_tokenize.
Removing Stop Words: Filtering out common stop words to reduce the dataset's vocabulary size.
Stemming: Reducing words to their root form using NLTK's SnowballStemmer.
Joining Review Text: Converting the list of words back into space-separated strings.

# Neural Network Models
The project involves building three neural network models, each using a different numerical representation of the text data. The models are designed to understand the nuances of human language and accurately classify the sentiment of the reviews.

# Requirements
Python 3.x
Pandas
NumPy
Matplotlib
NLTK
BeautifulSoup
