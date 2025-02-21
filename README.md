# E-commerce-Customer-Reviews-Sentiment-Analysis

The Streamlit App Deployed: https://e-commerce-customer-reviews-sentiment-analysis-fppusyq8bxp5g4k.streamlit.app/

Project Summary

This project is an Ecommerce Customer Reviews Sentiment Analysis App designed to transform raw customer feedback into actionable insights. The app leverages machine learning and natural language processing techniques to classify customer reviews as positive or negative, helping businesses quickly understand customer sentiment.

Key Components:
1)	Data Cleaning & Preprocessing:
The project includes comprehensive text cleaning routines to remove noise, special characters, URLs, and stopwords from raw review data.
2) Feature Extraction:
A TF-IDF vectorizer is used to convert text into numerical features that capture the importance of words within reviews.
3) Machine Learning Models:
Multiple classification models (including Random Forest, SVM, Logistic Regression, and XGBoost) are used. The final solution uses a combined pipeline (integrating the TF-IDF vectorizer with the sentiment classifier) for efficient predictions.
4) Interactive Web App:
Built with Streamlit, the user-friendly web interface allows users to input a review and instantly see its predicted sentiment. It loads a pre-trained sentiment analysis model (sentiment_model.pkl) and its corresponding TF-IDF vectorizer (tfidf_vectorizer.pkl), both of which rely on scikit-learn (sklearn).

This project provides a powerful yet accessible tool for analyzing customer reviews, enabling businesses to make data-driven decisions and improve overall customer satisfaction.
