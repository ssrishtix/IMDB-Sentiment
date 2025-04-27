# IMDB-Sentiment
## IMDb Movie Review - NLP Preprocessing
### Overview
This project is a case study comparing two text preprocessing techniques:

Stemming (using PorterStemmer)

Lemmatization (using WordNetLemmatizer)

The goal is to observe the impact on vocabulary size, text clarity, and information retention.



### Steps Performed
Cleaned the text: lowercasing, punctuation removal, digit removal, etc.

Removed custom stopwords.

Created two versions of the reviews: one stemmed, one lemmatized.

Analyzed and visualized the results using bar plots and word clouds.



### Results
Stemmed Vocabulary Size: ~22,000 words

Lemmatized Vocabulary Size: ~26,000 words

Conclusion:
Lemmatization preserved better semantic meaning and richer vocabulary compared to stemming.



### Technologies
Python

Pandas

NLTK

Matplotlib

Seaborn

WordCloud
