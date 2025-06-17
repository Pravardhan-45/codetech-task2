# Sentiment Analysis on News Articles (Scikit-learn 20 Newsgroups)

This repository contains a sentiment classification project using the `20 Newsgroups` dataset (specifically from `rec.autos` and `sci.med` categories) as a proxy for positive and negative sentiment. The goal is to classify article text as either **positive** or **negative** using machine learning.

---

## 📚 Dataset Description

- Dataset used: **Scikit-learn's 20 Newsgroups**  
- Categories used:
  - `rec.autos` → interpreted as **Negative**
  - `sci.med` → interpreted as **Positive**

This allows us to simulate a binary sentiment task using real-world text data.

---

## 🔍 Project Workflow

1. **Preprocessing**:
   - Removed headers, footers, and quotes
   - Applied TF-IDF vectorization

2. **Model**:
   - Logistic Regression trained on TF-IDF features
   - 80-20 train-test split

3. **Evaluation Metrics**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1)

---

## 🎯 Final Performance

- ✅ **Accuracy Score:** ~90%  
- 📋 **Classification Report:** Includes precision, recall, and F1 for both classes  
- 📊 Confusion matrix included for visual interpretation

---

## 🧠 Objective

- Learn end-to-end sentiment analysis on text
- Apply scikit-learn pipelines: vectorization → training → evaluation
- Visualize and interpret results

---

## 💻 Requirements

Before running the code, ensure the following dependencies are installed:

```bash
pip install pandas scikit-learn matplotlib seaborn
