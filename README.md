# Email_Spam_Detection
# 📧 Email Spam Detection using Multinomial Naive Bayes

## 📌 Project Overview

This project is a Machine Learning-based spam detection system that classifies SMS or email messages as **Spam** or **Ham (Not Spam)** using the **Multinomial Naive Bayes** algorithm. The model is trained on the SMS Spam Collection Dataset and uses **TF-IDF Vectorization** for feature extraction.

---

## 🎯 Objectives

- Automatically detect spam messages.
- Classify messages into Spam and Ham.
- Reduce unwanted messages.
- Demonstrate the use of Machine Learning in text classification.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- TF-IDF Vectorizer
- Multinomial Naive Bayes

---

## 📂 Dataset

**Dataset Name:** SMS Spam Collection Dataset

**Total Records:** 5572

**Features:**
- **Label:** Spam or Ham
- **Message:** SMS text

---

## ⚙️ Project Workflow

1. Load the dataset.
2. Remove unnecessary columns.
3. Rename the columns.
4. Convert labels (Ham = 0, Spam = 1).
5. Split the dataset into training and testing sets.
6. Convert text into numerical features using TF-IDF.
7. Train the Multinomial Naive Bayes model.
8. Predict Spam or Ham.
9. Evaluate model performance.

---

## 📊 Exploratory Data Analysis

The following visualizations were performed:

- Spam vs Ham Count
- Message Length Distribution
- Spam vs Ham Percentage (Pie Chart)

---

## 🤖 Machine Learning Algorithm

### Multinomial Naive Bayes

This algorithm is chosen because:

- Simple and fast
- Suitable for text classification
- Performs well with TF-IDF features
- Produces high accuracy

---

## 📈 Results

**Model Accuracy:** **96.28%**

The model successfully classified spam and legitimate messages with high accuracy.

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🧪 Sample Predictions

### Input

Congratulations! You have won ₹10,000. Click here to claim your prize.

**Prediction:** Spam

---

### Input

Hi Meghana, are you coming to college tomorrow?

**Prediction:** Not Spam

---

## 📁 Project Structure

```
Email-Spam-Detection/
│
├── spam.csv
├── Email_Spam_Detection.ipynb
├── README.md
├── screenshots/
├── Email_Spam_Ham_report/
└── Email_spam_detection_presentation/
```

---

## 🚀 Future Scope

- Detect phishing emails.
- Support multiple languages.
- Improve accuracy using Deep Learning.
- Develop a web-based spam detection application.

---

## 📚 References

- SMS Spam Collection Dataset
- Scikit-learn Documentation
- Python Documentation
- Google Colab Documentation

---



