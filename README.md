# 📩 Spam Message Classifier using Machine Learning

A complete **SMS Spam Detection Project** built with **Python** and **Scikit-learn**.
This model classifies messages into:

* **HAM** 🟢 → Normal / Safe Message
* **SPAM** 🔴 → Promotional / Fraud / Unwanted Message

---

# 🚀 Project Overview

This project uses:

* **TF-IDF Vectorization** for text feature extraction
* **Logistic Regression** for classification
* **Scikit-learn Metrics** for evaluation
* **Joblib** for saving trained model

---

# 📂 Dataset Used

**SMS Spam Collection Dataset**

* Total Messages: **5572**
* Ham Messages: **4825**
* Spam Messages: **747**

---

# ⚙️ Technologies Used

```python
Python
Pandas
NumPy
Scikit-learn
Joblib
```

---

# 🔍 Machine Learning Workflow

```text
Load Dataset
↓
Clean Data
↓
Convert Labels (ham=0, spam=1)
↓
Train Test Split
↓
TF-IDF Vectorization
↓
Train Logistic Regression
↓
Evaluate Model
↓
Save Model
```

---

# 📊 Model Performance

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 97.04% |
| Precision | 1.0000 |
| Recall    | 0.7785 |
| F1 Score  | 0.8755 |

---

# 📈 Classification Report

```text
              precision    recall  f1-score   support

HAM            0.97       1.00      0.98      966
SPAM           1.00       0.78      0.88      149

accuracy                             0.97     1115
macro avg       0.98       0.89      0.93     1115
weighted avg    0.97       0.97      0.97     1115
```

---

# 🧠 Confusion Matrix

```text
[[966   0]
 [ 33 116]]
```

### Breakdown:

* ✅ True HAM = 966
* ✅ True SPAM = 116
* ❌ Spam missed as Ham = 33
* ❌ Ham marked as Spam = 0

---

# 🧪 Real Message Testing

## Spam Examples

```text
CONGRATULATIONS! You have won a $1000 Walmart gift card
→ SPAM 🔴

FREE entry to win iPhone 15
→ SPAM 🔴
```

## Normal Examples

```text
Hey, are we still meeting for coffee tomorrow?
→ HAM 🟢

Don't forget to pick up milk and bread
→ HAM 🟢
```

---

# 💾 Saved Files

After training:

```text
spam_classifier.pkl
vectorizer.pkl
```

These files can be reused without retraining.

---

# ▶️ How to Run

```bash
pip install pandas numpy scikit-learn joblib
python spam_classifier.py
```

---

# 📁 Project Structure

```text
Spam-Classifier/
│── sms_spam_collection.csv
│── spam_classifier.py
│── spam_classifier.pkl
│── vectorizer.pkl
│── README.md
```

---

# 🎯 Future Improvements

* Use Naive Bayes / SVM / XGBoost
* Deep Learning (LSTM / GRU)
* Deploy with Flask / FastAPI
* Build Web Interface
* Real-time Email Spam Detection

---

# 🤝 Author

**Misbah Uddin**

AI/ML Engineer | 

\
