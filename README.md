# SENTIMENT-ANALYSIS-ON-GREEN-ENERGY
Overview
This project analyzes public sentiment towards sustainability, particularly climate action and green energy, using data collected from Twitter (now X). By leveraging machine learning and natural language processing (NLP) techniques, it explores how users feel about key environmental issues and assesses their engagement with sustainability topics.

Data & Methodology
Data Source: 96,558 tweets collected via the Tweet Binder API from February to October 2023.
Preprocessing: Techniques such as emoji removal, tokenization, and lemmatization were applied to clean the data.
Sentiment Classification: The tweets were categorized into Positive, Neutral, and Negative sentiment using NLTK's Sentiment Intensity Analyzer (SIA).
Machine Learning Models
Naive Bayes
Support Vector Machine (SVM)
Recurrent Neural Networks (RNN) with Fast-Text and GloVe embeddings
DistilBERT
BERT
Key Findings
BERT Model achieved the highest classification accuracy at 98%, making it the most effective for sentiment analysis.
Sentiment Breakdown: 58.4% of tweets were positive towards sustainability, 19.5% were negative, and 22.1% were neutral.
