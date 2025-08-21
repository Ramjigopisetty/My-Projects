# 📧 Email Spam Detector

A Natural Language Processing (NLP) project that detects spam emails using **Naive Bayes Classifier** and **TF-IDF vectorization**.

---

## 🚀 Features
- Text preprocessing & cleaning
- Feature extraction with **TfidfVectorizer**
- Spam/Not Spam classification
- Accuracy and classification report
- User input for real-time predictions

---

## ⚙️ Installation
```bash
pip install pandas numpy scikit-learn
```

---

## ▶️ Usage
```bash
python email_spam_detector.py
```

Enter an email text when prompted to check if it is **Spam** or **Not Spam**.

---

## 📊 Example Output
```
Accuracy: 0.97
Classification Report:
              precision    recall  f1-score   support
           0       0.98      0.97      0.98      965
           1       0.95      0.96      0.96      150

Predicted: Spam
Predicted: Not Spam
```
