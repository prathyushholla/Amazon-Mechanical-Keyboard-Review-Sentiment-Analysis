# Amazon Mechanical Keyboard Review Sentiment Analysis

This project utilizes web scraping and machine learning to analyze customer sentiment for a mechanical keyboard on Amazon. The objective is to gather insights into customer satisfaction and feedback using Natural Language Processing(NLP).

# Project Overview
The goal of this project is to gather and analyze customer reviews from Amazon for the MageGee Portable Mechanical Keyboard. By using a multi-lingual BERT model for sentiment analysis, we aim to determine the overall sentiment of customer reviews.
Mechanical Keyboard: https://www.amazon.com/Portable-Mechanical-Keyboard-MageGee-Backlit/dp/B098LG3N6R/ref=cm_cr_arp_d_product_top?ie=UTF8&th=1

# Data Collection
Using web scraping techniques, this project extracts review data directly from the Amazon product page. The web scraping process focuses on:
- Extracting review text from each review.
- Filtering and cleaning the reviews for further analysis.

# Model 
This project leverages the multi-lingual BERT model from Hugging Face (nlptown/bert-base-multilingual-uncased-sentiment) to perform sentiment analysis. The BERT model is ideal for understanding the sentiment in multilingual reviews as it supports several languages, enabling analysis across diverse user demographics.
Key model features:
- The model returns sentiment scores on a scale (e.g., 1-5 stars) based on customer reviews.
- Supports multiple languages, which allows for a broader analysis of global reviews.
  
model: https://huggingface.co/nlptown/bert-base-multilingual-uncased-sentiment
