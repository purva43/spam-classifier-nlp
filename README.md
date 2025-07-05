# 📧 Email/SMS Spam Classifier - NLP Project

This project is a simple **Natural Language Processing (NLP)** application that classifies text messages as **Spam** or **Not Spam**. It uses a machine learning model trained on labeled data and deployed with saved `.pkl` files.

---

## 🚀 Project Overview

- **Type:** Binary Text Classification
- **Techniques:** Text Preprocessing, TF-IDF, Multinomial Naive Bayes
- **Tools Used:** 
  - Python
  - Jupyter Notebook
  - Scikit-learn
  - NLTK
  - Pickle (for model saving)

---

## 🧠 Key Features

- Preprocess raw text (lowercasing, removing punctuation, stop words, etc.)
- Convert text into numerical form using **TF-IDF vectorizer**
- Train a **Naive Bayes classifier**
- Save the model and vectorizer for later use
- Predict whether a message is spam or not

---

## 📁 Project Structure

Email_Spam_Classifier/
├── Email_Spam_Classifier.ipynb # Main Jupyter notebook
├── model.pkl # Trained spam classifier model
├── vectorizer.pkl # TF-IDF vectorizer
├── requirements.txt # Required Python packages
└── README.md # Project documentation



## 📁 Files Included

- `SpamClassifier.ipynb`: Jupyter Notebook with full code
- `requirements.txt`: List of libraries required
- `README.md`: Project documentation (this file)

---

## 🛠️ How to Run the Project

1. Clone the repo or download the files
## install the required packages
pip install -r requirements.txt

## open the notebook
jupyter notebook Email_Spam_Classifier.ipynb
