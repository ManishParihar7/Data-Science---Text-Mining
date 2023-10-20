# Data-Science---Text-Mining
# Sentiment Analysis and Product Review Extraction from E-commerce Website

## Problem Statement - 1: Sentiment Analysis on Elon Musk Tweets

### Introduction

The project aims to perform sentiment analysis on tweets made by Elon Musk. Sentiment analysis helps in understanding the emotional tone, attitude, or opinion expressed in the text. In this case, we analyze Elon Musk's tweets to gauge the sentiment, whether it's positive, negative, or neutral.

### Table of Contents

- [Introduction](#introduction)
- [Data Preprocessing](#data-preprocessing)
- [Sentiment Analysis](#sentiment-analysis)
- [Conclusion](#conclusion)
- [Author](#author)
- [License](#license)

### Data Preprocessing

The code begins by preprocessing the text data extracted from Elon Musk's tweets. It involves several steps, including:

1. Removing non-alphabetic characters.
2. Converting text to lowercase.
3. Splitting text into words.
4. Removing stopwords.
5. Stemming words.
6. Rejoining processed words into text.

### Sentiment Analysis

The sentiment analysis is performed using the TextBlob library. Sentiment scores are assigned to each tweet, indicating polarity (positive, negative, or neutral). The sentiment score results are then analyzed and visualized.

## Problem Statement - 2: Extracting Product Reviews from an E-commerce Website

### Introduction

This project focuses on extracting product reviews from an e-commerce website, specifically Amazon. The goal is to scrape and preprocess reviews for further analysis.

### Table of Contents

- [Introduction](#introduction-1)
- [Web Scraping](#web-scraping)
- [Data Preprocessing](#data-preprocessing-1)
- [Sentiment Analysis](#sentiment-analysis-1)
- [Conclusion](#conclusion-1)
- [Author](#author)
- [License](#license)

### Web Scraping

The code utilizes the BeautifulSoup library and the requests module to scrape reviews from a product page on Amazon. Multiple pages of reviews are scraped and stored in a list.

### Data Preprocessing

The reviews are preprocessed, involving the following steps:

1. Removing non-alphabetic characters.
2. Converting text to lowercase.
3. Splitting text into words.
4. Removing stopwords.
5. Stemming words.
6. Rejoining processed words into text.

### Sentiment Analysis

Sentiment analysis is conducted using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. Sentiment scores are assigned to reviews, and categories (positive, negative, or neutral) are determined based on the scores.

### Conclusion

The README provides an overview of the two projects, which involve sentiment analysis on Elon Musk's tweets and the extraction of product reviews from an e-commerce website. These projects demonstrate the application of sentiment analysis and web scraping techniques for text data.

## Author

[Manish Parihar]

## License

This project is licensed under the MIT License.

---

**Author:** [Manish Parihar]
