This project is about predicting that a news is fake or not using essential python libraries and fake_news_prediction dataset
Libraries used:
numpy
pandas
regex
from nltk.corpus import stopwords
from nltk.stem.porter import PorterStemmer
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
Dataset: https://www.kaggle.com/c/fake-news/da...
