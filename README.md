# 📩 SMS Spam Classifier (NLP Project)

## 📌 Problem Statement

Build a machine learning model to classify SMS messages as **Spam or Ham (Not Spam)** using Natural Language Processing techniques.

---

## 🚀 Project Overview

This project uses NLP and Machine Learning to automatically detect spam messages.

---

## 📊 Dataset

* SMS Spam Collection Dataset
* Contains labeled messages: spam / ham

---

## 🔧 Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* NLTK
* Matplotlib

---

## 🧠 Steps Performed

### 1. Data Cleaning & EDA

* Removed unnecessary columns
* Checked class distribution (imbalanced dataset)
* Created message length feature
* Visualized data

### 2. Text Preprocessing

* Lowercasing
* Removing punctuation
* Removing stopwords

### 3. Feature Extraction

* TF-IDF Vectorization

### 4. Model Building

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

### 5. Model Evaluation

* Accuracy
* Precision
* Recall
* F1-score

---

## 📈 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Naive Bayes         | 96.7%    |
| Logistic Regression | 95%      |
| SVM                 | **98%**  |

👉 **Best Model: SVM**

---

## 🏁 Conclusion

* SVM performed the best with highest accuracy and balanced precision-recall
* Model can effectively classify spam messages

