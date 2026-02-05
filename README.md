# Naive Bayes Classifier: From Numeric Data to NLP

This repository contains a practical implementation of the Naive Bayes algorithm using Python and Scikit-Learn. The project demonstrates how to handle different types of data—continuous numeric values and discrete text—to solve real-world classification problems.

## 🚀 Overview

Naive Bayes is a powerful probabilistic classifier based on Bayes' Theorem. This project explores two specific variants:
1. **Gaussian Naive Bayes:** Applied to medical diagnostic data.
2. **Multinomial Naive Bayes:** Applied to Natural Language Processing (NLP) tasks.

## 🛠️ Technologies Used

- **Language:** Python 3.x
- **Libraries:**
  - `scikit-learn`: Model implementation and evaluation
  - `pandas` & `numpy`: Data manipulation
  - `matplotlib` & `seaborn`: Data visualization

## 📂 Project Structure

### Part A: Numeric Classification (Breast Cancer Diagnosis)
Using the **Breast Cancer Wisconsin Dataset**, we implement a Gaussian Naive Bayes model to classify tumors as **Malignant** or **Benign**.
* **Feature Set:** 30 continuous numeric measurements (mean radius, texture, perimeter, etc.).
* **Process:** Data exploration -> Train/Test split -> Model training -> Performance evaluation.

### Part B: Text Classification (NLP)
We demonstrate how to process raw text for machine learning using the **20 Newsgroups** dataset and a custom sentiment analysis example.
* **Technique:** Utilizes `CountVectorizer` to transform text into numerical "Bag-of-Words" vectors.
* **Model:** Implements `MultinomialNB`, the industry standard for document classification based on word counts.

## 📊 Evaluation Metrics

The models are evaluated using robust machine learning metrics to ensure reliability:
- **Accuracy Score**: Overall correctness.
- **Confusion Matrix**: Visualizing True Positives vs. False Positives.
- **Classification Report**: Detailed breakdown of **Precision**, **Recall**, and **F1-Score**.

## 💻 How to Use

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/naive-bayes-classifier.git](https://github.com/yourusername/naive-bayes-classifier.git)
