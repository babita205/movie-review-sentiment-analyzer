# 🎬 Sentiment Analyzer for Movie Reviews

An AI-powered web tool that analyzes movie reviews and classifies them as **Positive, Negative, or Neutral** using Natural Language Processing.

## 🚀 Features

* Sentiment prediction using **Naive Bayes**
* NLP preprocessing using **NLTK**
* Clean interactive UI using **Gradio**
* Displays sentiment confidence scores

## 🧠 Technologies Used

* Python
* NLTK
* Scikit-learn
* TF-IDF Vectorization
* Naive Bayes Classifier
* Gradio

## 📊 How It Works

1. User enters a movie review
2. Text is cleaned using NLP preprocessing
3. TF-IDF converts text into numerical features
4. Naive Bayes model predicts sentiment


## 📷 Example Output


Input:

> "The movie was amazing with great acting."

Prediction:
Positive Sentiment

Confidence Scores:
Positive: 82%
Negative: 10%
Neutral: 8%

## 📌 Future Improvements

* Train with full IMDB dataset
* Add sentiment visualization charts
* Deploy as a web app
