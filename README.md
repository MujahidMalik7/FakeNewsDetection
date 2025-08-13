# Fake News Detection System

A **machine learning-based web application** that classifies news articles as **Real** or **Fake** based on their text content. The system uses **TF-IDF vectorization** and two classifiers: **Logistic Regression** and **Linear SVM (LinearSVC)**. Users can test any news article through a **Streamlit web app** to get instant predictions.

---

## Features
- Preprocesses text by converting to lowercase, removing punctuation, numbers, stopwords, and non-ASCII characters.  
- Lemmatizes text for better feature representation.  
- Classifies news using:  
  - **Logistic Regression**  
  - **LinearSVC (SVM)**  
- Interactive **Streamlit interface** for testing single articles.  
- Pre-trained models and vectorizer stored in a **`Models/` folder** for easy deployment.  

---

## Technologies Used
- Python 3  
- scikit-learn (Logistic Regression, LinearSVC, TF-IDF)  
- NLTK (stopwords, lemmatization)  
- Streamlit (web interface)  
- Pickle (model serialization)  

---

## Author
- Developed by **Mujahid**  

---

## Dataset
Original dataset used: [Fake and Real News Dataset on Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)

---


## Tags
`Fake News` `Machine Learning` `Text Classification` `Natural Language Processing` `TF-IDF` `Logistic Regression` `SVM` `Streamlit` `Python` `NLP`
