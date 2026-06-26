# 📰 Fake News Detection System
**International Islamic University, Islamabad (IIUI)**
**Course:** Artificial Intelligence
**Instructor:** Shakeel Ahmad
**Group:** 12
**Department:** Software Engineering (BSSE)

---

## 📌 Project Overview
This project builds an automated **Fake News Detection System** using Natural Language Processing (NLP) and Machine Learning. It classifies news articles as **FAKE** or **REAL** using two ML models trained on real Kaggle data.

---

## 🛠️ Techniques Used
- **Text Preprocessing** — cleaning, stopword removal
- **TF-IDF Vectorization** — with bigrams (ngram_range 1,2)
- **Logistic Regression** — baseline ML model
- **Random Forest Classifier** — ensemble ML model

---

## 📊 Dataset
- Source: [Fake and Real News Dataset — Kaggle](https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset)
- Fake.csv — 23,481 fake news articles
- True.csv — 21,417 real news articles
- Total: ~44,898 articles

---

## ✅ Results
| Model | Accuracy | F1-Score | ROC-AUC |
|---|---|---|---|
| Logistic Regression | ~99% | ~99% | ~0.999 |
| Random Forest | ~99% | ~99% | ~0.999 |

---

## 📋 Requirements
pip install pandas numpy matplotlib seaborn scikit-learn wordcloud notebook

---

## ▶️ How to Run
1. Install Anaconda from anaconda.com
2. Place Fake.csv and True.csv in same folder as notebook
3. Open Anaconda Prompt → type: jupyter notebook
4. Open Fake_News_Detection_Group12.ipynb
5. Click Kernel → Restart and Run All

---

## 📁 Project Structure
- Fake_News_Detection_Group12.ipynb — Main project notebook
- Fake.csv — Fake news dataset
- True.csv — Real news dataset
- README.md — Project documentation

---

*Submitted to: Shakeel Ahmad | IIUI | Artificial Intelligence Course | Group 12*
