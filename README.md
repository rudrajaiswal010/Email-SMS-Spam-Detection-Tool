# Email-SMS-Spam-Detection-Tool
 #  Email/SMS Spam Detection using Machine Learning

A machine learning-based project that classifies messages as **spam** or **ham (not spam)** using natural language processing (NLP) and classification algorithms. The model is trained on a public dataset and is capable of detecting unwanted messages with high accuracy.

---

##  Project Overview

This project applies machine learning techniques to detect spam messages in SMS or email texts. It involves cleaning and processing the raw text, converting it into numerical features, and training a classifier to make predictions.

---

## Features

- Text preprocessing (lowercasing, tokenization, stop word removal, stemming)
- Feature extraction using **TF-IDF Vectorizer**
- Trained with popular ML models:
  - Naive Bayes
  - Logistic Regression
  - Support Vector Machines (optional)
- Model evaluation with accuracy, precision, recall, and F1-score
- Clean and simple implementation in Python

---

##  Technologies Used

- **Python**
- **scikit-learn** – ML algorithms & model evaluation
- **pandas & numpy** – data manipulation
- **nltk** – natural language preprocessing
- **matplotlib** – data visualization
- **Jupyter Notebook** – for analysis and experimentation

---

##  Dataset

- [SMS Spam Collection Dataset (UCI)](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- The dataset contains labeled messages as "spam" or "ham" for supervised learning.

---

##  Getting Started

###  Prerequisites

Install the required libraries using:

```bash
pip install -r requirements.txt
