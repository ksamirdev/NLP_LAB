# NLP Assignments Repository

**Text Preprocessing & Sentiment Analysis Projects**

This repository contains two Natural Language Processing (NLP) assignments demonstrating fundamental and applied NLP techniques using Python, NLTK, and Machine Learning models.

Both assignments focus on understanding how raw text is transformed into meaningful data for computational analysis and prediction.

---

## 📌 Assignments Included

### ✅ Assignment 1 – NLP Text Preprocessing Pipeline

Implements a complete NLP preprocessing workflow on a custom paragraph, displaying the results at each stage.

#### Steps Covered:

* Tokenization
* Stopword Removal
* Stemming
* Lemmatization

#### Purpose:

To demonstrate how raw text is cleaned and normalized before being used in NLP tasks or machine learning models.

#### File:

* `NLP_LAB/Assignment1.ipynb`

---

### ✅ Assignment 2 – Sentiment Analysis Using Machine Learning

Builds a full end-to-end sentiment analysis model that classifies text as **Positive** or **Negative** using a large real-world dataset.

#### Objective:

To design an accurate sentiment classification pipeline using modern NLP and ML techniques.

---

## 📖 Assignment 2 – Project Overview

This project implements a Sentiment Analysis system using the **NLTK Movie Reviews Dataset**.

### Dataset Details:

* Positive Reviews: 1000
* Negative Reviews: 1000
* Total Reviews: 2000
* Balanced and suitable for classification tasks

---

## 🔧 Pipeline Workflow

1. **Load Dataset**

   * Dataset imported from NLTK and combined with labels.

2. **Data Cleaning**

   * Lowercasing
   * Removing punctuation
   * Removing special characters

3. **Feature Extraction**

   * TF-IDF Vectorization using `TfidfVectorizer`

4. **Model Training**

   * Logistic Regression classifier

5. **Model Evaluation**

   * Accuracy Score
   * Confusion Matrix
   * Performance testing

6. **Custom Prediction**

   * Allows user-input sentences for live sentiment prediction.

**Expected Accuracy:** 80% – 92%

---

## 🧪 Technologies Used

* Python
* NLTK
* Scikit-learn
* Machine Learning
* TF-IDF Vectorization
* Logistic Regression
* Google Colab / Jupyter Notebook

---

## 📁 Repository Structure

```
NLP_LAB/
│
├── Assignment1.ipynb
│
├── Assignment2.ipynb
│
├── README.md
```

---

## ▶️ How to Run

### Option A: Google Colab

1. Open the notebook file.
2. Connect to runtime.
3. Run all cells sequentially.
4. Enter custom text for prediction (Assignment 2).

### Option B: Local Machine

Install required libraries:

```bash
pip install nltk scikit-learn
```

Then run the notebooks using Jupyter Notebook or VS Code.

---

## 🎯 Learning Outcomes

* Understanding of NLP preprocessing techniques
* Practical implementation of TF-IDF
* Training and evaluating ML classifiers
* Insight into real-world sentiment analysis systems
* Comparing basic NLP processing with applied ML use cases
