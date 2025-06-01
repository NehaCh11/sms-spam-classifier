# 📩 SMS Spam Classifier

This project is a simple machine learning application that detects whether a given SMS message is **spam** or **not spam**. It uses natural language processing (NLP) and a classification model built with scikit-learn and NLTK. The app is powered by a Streamlit interface for live testing.

---

## 🚀 Features

- Clean and simple web interface using Streamlit
- Text preprocessing: lowercasing, tokenization, stopword removal, stemming
- TF-IDF vectorization
- Trained classification model (e.g., Naive Bayes, SVM, etc.)
- Real-time prediction

---

## 🧠 Technologies Used

- Python
- Streamlit
- scikit-learn
- NLTK
- Pickle (for model serialization)

---

## 💻 How to Run

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt

streamlit run App.py

## FOLDER STRUCTURE

sms-spam-classifier/
├── App.py                 # Streamlit app
├── model.pkl              # Trained model
├── vectorizer.pkl         # TF-IDF vectorizer
├── requirements.txt       # Required packages
├── README.md              # Project documentation


##🌐 Live Demo
##🔗 https://sms-spam-search.streamlit.app/



