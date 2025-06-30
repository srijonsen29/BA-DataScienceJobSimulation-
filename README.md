# British Airways Customer Review Analysis & Booking Prediction

## Project Overview

This project combines **Natural Language Processing (NLP)** and **Machine Learning (ML)** to analyze customer reviews for British Airways and build a predictive model to forecast booking completion. It aims to identify key factors impacting customer decisions and use historical booking data to predict future booking behavior.

---

## Objectives

- Perform **sentiment analysis** on customer reviews to identify pain points and service expectations.
- Analyze **behavioral and transactional data** to predict the likelihood of booking completion.
- Build a **Random Forest Classifier** to interpret feature importance and understand predictive power.
- Generate insights to help British Airways **optimize customer engagement** and **marketing strategies**.

---

## Project Structure

## Techniques Used

### NLP on Customer Reviews
- **Text Preprocessing**: Tokenization, Stopword Removal, Lemmatization (using `NLTK`)
- **Sentiment Scoring**: Polarity scores using `TextBlob` or `VADER`
- **Visualization**: Word clouds, sentiment distribution with `Matplotlib` and `Seaborn`

### Predictive Modelling
- **Preprocessing**: Missing value handling, One-hot encoding, Feature selection
- **Model**: `RandomForestClassifier` from `scikit-learn`
- **Evaluation Metrics**:
  - Accuracy: `85.00%`
  - ROC AUC: `0.7836`
  - Average CV Score: `0.6920`
- **Feature Importance**: Bar chart of top 10 features contributing to booking prediction

---

## Key Insights

- **Sentiment Analysis** revealed that delays, customer service, and flight comfort significantly affect booking perception.
- The **predictive model** identified `Lead Time`, `Flight Day`, `Booking Source`, and `Cabin Class` as top predictors.
- Class imbalance indicates the need for enhanced modelling techniques to boost recall on booking completions.

---

## Technologies

- **Python 3.x**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`, `nltk`, `TextBlob`, `VADER`
- `jupyter-notebook`

---

## Deliverables

- Review analysis report
- Predictive modelling notebook
- Summary slide for stakeholders

---

