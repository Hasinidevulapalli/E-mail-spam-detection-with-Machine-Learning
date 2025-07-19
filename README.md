# Task 4: Email Spam Detection

This project uses machine learning to classify SMS messages as spam or ham (not spam) using the SMS Spam Collection dataset. A Multinomial Naive Bayes classifier was trained on preprocessed text data and achieved an accuracy of approximately 98%.

## Features
- Data cleaning and preprocessing
- Exploratory data analysis with visualizations
- WordClouds for spam and ham messages
- Text vectorization using CountVectorizer
- Spam detection using Naive Bayes classifier
- Custom message classification
- Model evaluated using confusion matrix and classification report
- Balanced performance across precision, recall, and F1-score

## How to Run
1. Clone this repository
2. Install required libraries:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn wordcloud
