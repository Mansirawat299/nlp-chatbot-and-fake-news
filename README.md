# NLP — Assignment 4  
**Unit 4: Chatbots, Fake News Detection & Social Media Analytics**

**Author:** Mansi Rawat

---

## Overview
This repository implements Assignment 4 of the NLP lab. It contains a compact, reproducible demonstration of:

- **Task 1 — Chatbot (Intent Detection)**  
  - Intent classification (greeting, query, feedback) using TF-IDF and Logistic Regression, plus rule-based overrides and fallback handling.
- **Task 2 — Fake News Detection**  
  - Binary classification (real vs fake) using TF-IDF (word + char options) and Logistic Regression. Evaluation with stratified cross-validation, confusion matrix, and inspection of top n-grams.
- **Task 3 — Ethical & Social Implications**  
  - Short discussion on ethical concerns and mitigations for chatbots and fake-news systems.

> The interactive notebook with the full code and results is available at: `/mnt/data/NLP_Assignment4.ipynb`

---

---

## 🧠 Task 1 — Chatbot (Intent Detection)

### ✔ Features
- Preprocessing:  
  Lowercasing, punctuation removal, lemmatization, stopword removal.
- Vectorization: **TF-IDF (word-level)**
- Model: **Logistic Regression**
- Rule-based fallback for greetings, unknown queries.
- Interactive chatbot loop in notebook.

---

## 📰 Task 2 — Fake News Detection

### ✔ Dataset  
A **small toy dataset** of 10 fake/real headlines (self-contained, no external files).

### ✔ Steps Implemented
- Preprocessing of text  
- TF-IDF vectorization (1–2 grams)  
- Logistic Regression classifier  
- Stratified K-Fold accuracy  
- Classification Report  
- Confusion Matrix heatmap  
- WordCloud for real vs fake news  

## ⚖️ Task 3 — Ethical & Social Implications

### **Chatbots — Ethical Concern**
They may generate **incorrect or biased responses**.

**Mitigation:**  
Use response confidence thresholds, disclaimers, human review, and bias monitoring.

---

### **Fake-News Systems — Ethical Concern**
False positives can **mislabel real news as fake**, harming trust.

**Mitigation:**  
Use balanced datasets, explainable models, and manual review/appeal processes.

---
