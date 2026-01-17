# SQL Injection Detection using Random Forest

## 📌 Overview
A machine learning–based system to detect **SQL Injection attacks** using **TF-IDF vectorization** and a **Random Forest Classifier**. The model classifies SQL queries as **malicious** or **safe**.

---

## 🚀 Features
- Detects common SQL injection patterns
- Uses TF-IDF for text feature extraction
- Random Forest for robust classification
- Supports real-time query prediction

---

## 🧠 Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn

---

## 📂 Files
- `sql.xlsx` – Dataset
- `sql.pkl` – Trained Random Forest model
- `tfidf_vector.pkl` – TF-IDF vectorizer
- `README.md` – Project documentation

---

## 🔍 Example Usage
```python
sql_detect("OR 1 = 1 --")
```
Output:
```
SQL injection detected
```

---

## 📊 Evaluation
- Accuracy score
- Confusion matrix

---

## 🔐 Use Cases
- Web application security
- Input validation
- API protection

---



