📧 Spam Detection System

An end-to-end Natural Language Processing (NLP) project that classifies text messages as **Spam** or **Ham (Legitimate)** using machine learning techniques. The project covers text preprocessing, feature extraction using CountVectorizer and TF-IDF, model training, evaluation, and deployment through a reusable prediction pipeline.



 📊 Overview

Spam messages are a common challenge in communication platforms. This project leverages NLP and Machine Learning to automatically identify unwanted messages while minimizing false alarms.

The system processes raw text, converts it into numerical features, trains classification models, and predicts whether a message is spam or legitimate.

Users can:

* Analyze and preprocess text data
* Compare vectorization techniques
* Train and evaluate classification models
* Visualize model performance
* Predict new messages instantly
* Save and reload trained models for deployment



 ✨ Features

📝 Text Preprocessing

* Lowercasing text
* Removing punctuation and special characters
* Tokenization
* Stopword removal
* Text normalization
* Noise reduction

 🔤 Feature Extraction

Convert text into numerical vectors using:

* CountVectorizer (Bag of Words)
* TF-IDF Vectorizer

Compare both approaches to determine the most effective text representation.

 🤖 Machine Learning Models

* Multinomial Naive Bayes
* Logistic Regression

Train and compare multiple models for spam classification.

 📊 Performance Evaluation

Evaluate models using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

 📈 Confusion Matrix Analysis

Visualize:

* Correct classifications
* False Positives
* False Negatives
* Model strengths and weaknesses

 💾 Model Persistence

Save the complete pipeline including:

* Text Vectorizer
* Trained Model

Reload the pipeline anytime for instant predictions without retraining.

 🔮 Spam Prediction Tool

Input any message and receive:

* Spam/Ham Classification
* Confidence Score
* Probability Distribution
* Real-Time Prediction



 🧠 Machine Learning Pipeline

 Dataset

SMS Spam Collection Dataset

* Labeled Spam and Ham Messages
* Text-Based Classification Dataset

 Data Preprocessing

* Text Cleaning
* Tokenization
* Stopword Removal
* Feature Engineering

 Feature Extraction

 CountVectorizer

Converts text into word-frequency vectors.

TF-IDF Vectorizer

Measures word importance relative to the entire dataset.

 Models

 Multinomial Naive Bayes

A probabilistic classifier commonly used in NLP applications.

 Logistic Regression

A linear classification model that predicts spam probabilities.



 📋 Workflow

```text
Raw Messages
      ↓
Text Cleaning
      ↓
Tokenization
      ↓
Vectorization (TF-IDF / CountVectorizer)
      ↓
Model Training
      ↓
Evaluation
      ↓
Pipeline Saving
      ↓
Real-Time Prediction
```



 📊 Model Evaluation Metrics

| Metric    | Description                                                  |
| --------- | ------------------------------------------------------------ |
| Accuracy  | Overall prediction correctness                               |
| Precision | Percentage of predicted spam messages that are actually spam |
| Recall    | Percentage of actual spam messages detected                  |
| F1-Score  | Balance between precision and recall                         |

 Why Precision & Recall Matter

* High Precision reduces false spam alerts.
* High Recall ensures spam messages are not missed.
* F1-Score balances both objectives.



 🛠️ Technologies Used

 Machine Learning & NLP

* Python
* Scikit-learn
* Pandas
* NumPy
* NLTK

 Feature Engineering

* CountVectorizer
* TF-IDF Vectorizer

 Model Persistence

* Joblib
* Pickle

 Visualization

* Matplotlib
* Seaborn



 📸 Project Components

 Data Exploration

* Class Distribution
* Word Frequency Analysis
* Message Length Distribution

 Feature Analysis

* Most Common Spam Words
* Most Common Ham Words
* TF-IDF Feature Importance

 Model Comparison

* Naive Bayes vs Logistic Regression
* Accuracy Comparison
* Precision/Recall Analysis

 Prediction System

Users can enter custom messages and receive instant spam predictions.


🚀 Getting Started

 Clone the Repository

```bash
git clone https://github.com/yourusername/spam-detection-system.git

cd spam-detection-system
```

 Install Dependencies

```bash
pip install -r requirements.txt
```

Train the Model

```bash
python train.py
```

 Run Predictions

```bash
python predict.py
```

 Load Saved Pipeline

```python
import joblib

pipeline = joblib.load("spam_detector.pkl")

prediction = pipeline.predict([
    "Congratulations! You have won a free iPhone."
])

print(prediction)
```

 📈 Sample Results

| Metric       | Value                   |
| ------------ | ----------------------- |
| Dataset Size | 5,500+ Messages         |
| Classes      | Spam / Ham              |
| Vectorizer   | TF-IDF                  |
| Best Model   | Multinomial Naive Bayes |
| Accuracy     | 98%+                    |
| Precision    | High                    |
| Recall       | High                    |
| F1-Score     | High                    |



 🎯 Learning Objectives

This project demonstrates:

* Natural Language Processing (NLP)
* Text Preprocessing
* Feature Extraction
* TF-IDF and Bag-of-Words
* Supervised Machine Learning
* Classification Metrics
* Model Serialization
* Real-Time Prediction Systems



 🔮 Future Improvements

* Deep Learning with LSTM
* BERT-based Spam Classification
* Email Spam Detection
* Multi-language Support
* Web Application Deployment
* Streamlit Dashboard
* REST API Integration
* Real-Time Email Filtering

 📌 Key Highlights

✅ NLP-based Spam Classification

✅ Text Cleaning & Tokenization

✅ CountVectorizer & TF-IDF Comparison

✅ Naive Bayes & Logistic Regression Models

✅ Precision, Recall & F1 Evaluation

✅ Confusion Matrix Analysis

✅ Saved Prediction Pipeline

✅ Real-Time Spam Detection System

✅ Deployment-Ready Architecture
