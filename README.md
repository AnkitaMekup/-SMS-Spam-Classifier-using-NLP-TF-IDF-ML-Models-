# -SMS-Spam-Classifier-using-NLP-TF-IDF-ML-Models-
The goal of this project is to classify SMS messages as Spam or Ham (Not Spam) using Natural Language Processing techniques and Machine Learning models.

# Tech Stack
- Python
- Pandas, NumPy
- NLTK (text preprocessing)
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression, Naive Bayes

# Dataset
Dataset: SMS Spam Collection Dataset

# Data Preprocessing
- Removed special characters using regex
- Converted text to lowercase
- Removed stopwords
- Applied stemming (PorterStemmer)

# Feature Engineering
- Bag of Words (CountVectorizer)
- TF-IDF (Term Frequency - Inverse Document Frequency)

# Models Used
- Multinomial Naive Bayes
- Logistic Regression

# Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

# Live Prediction Function
The model can predict real-time SMS messages as:
- Spam 🚨
- Ham ✅

# Folder Structure (VERY IMPORTANT)
Spam-Classifier/
│
├── data/
│   └── SMSSpamCollection.txt
│
├── notebooks/
│   └── spam_classifier.ipynb
│
├── src/
│   └── preprocessing.py
│
├── model/
│   └── spam_model.pkl
│
├── README.md
└── requirements.txt

# Key Highlight
- Achieved ~98% accuracy
- Compared multiple ML models
- Implemented TF-IDF for better text representation
- Built real-time prediction function

- Logistic Regression
