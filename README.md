# 📧 Spam Mail Prediction Using Machine Learning

This project involves building a machine learning model to classify emails as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) techniques and a Logistic Regression model.

## 🔍 Overview
- Cleaned and preprocessed text data from a labeled dataset of emails.
- Applied **TF-IDF vectorization** for converting text into numerical features.
- Trained and tested a **Logistic Regression** model to perform binary classification.
- Achieved an accuracy of **~97%** on unseen data.

## 🧠 Technologies & Libraries
- **Python**
- **Pandas, NumPy** – Data handling
- **Sklearn** – Model training and evaluation
- **TfidfVectorizer** – Text feature extraction
- **Google Colab** – Development environment

## 📈 Model Pipeline
1. Load and inspect dataset (`mail_data.csv`)
2. Preprocess and clean data (null handling, label encoding)
3. Vectorize text using `TfidfVectorizer`
4. Split data into training and test sets
5. Train using `LogisticRegression`
6. Evaluate using `accuracy_score`

## 📊 Results
- **Model**: Logistic Regression
- **Accuracy**: ~97%
- The model performs well in distinguishing between spam and non-spam emails.

## 📁 Folder Structure
```
📦spam-mail-classifier
 ┣ 📜 spam_mail_prediction.ipynb
 ┣ 📜 README.md
 ┣ 📜 mail_data.csv (not included due to size/privacy)
```

## 📄 Note
Dataset file `mail_data.csv` is required to run the notebook. You can replace it with any public spam email dataset for experimentation.
