# Product Sentiment Analysis

## Overview

This project involves sentiment analysis on product reviews scraped from Flipkart. The goal is to analyze customer reviews for various products and determine their sentiment (Positive, Negative, or Neutral). The analysis is performed using multiple methods, including TextBlob and Vader Sentiment Analysis. The project also includes visualizations for a better understanding of the sentiment distribution and review insights.


## Dataset

The dataset consists of the following columns:

rating: Rating given by the customer (1-5).

review_summary: Summary of the customer review.

review_description: Detailed description of the customer review.

product_name: Name of the product being reviewed.

Price: Price of the product.

product_id: Unique identifier for each product.

compound: Compound sentiment score from Vader Sentiment.

compound_sentiment: Sentiment classification based on compound score.

rating_sentiment: Sentiment based on rating (Positive, Negative, or Neutral).

Sentiment: Sentiment from TextBlob (Positive, Negative, or Neutral).

Polarity: Polarity score from TextBlob.

TextBlob_Sentiment: Sentiment classification from TextBlob.


## Requirements

pandas

matplotlib

seaborn

textblob

nltk

wordcloud
