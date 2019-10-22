import pandas as pd # For dataframe manipulation

import nltk  # machine learning with text

from nltk.corpus import stopwords, wordnet  # List of common words

from nltk.tokenize import word_tokenize  # Split text into significant forms

from nltk.stem import WordNetLemmatizer  # Reduce words to their root form ("lemma")

from nltk import pos_tag  # Tag words with parts of speech

from collections import defaultdict  # Dictionaries that have a backup value

from sklearn.feature_extraction.text import CountVectorizer  # Convert text to sparse matrices

import matplotlib.pyplot as plt  # Complex visualisation configuration

import seaborn as sns  # Visualisation

from wordcloud import WordCloud  # Create wordclouds

from textblob import TextBlob  # Sentiment analysis
 
# Install necessary dependencies from NLTK
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')