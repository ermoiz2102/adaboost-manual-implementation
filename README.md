# ⚡ AdaBoost (Adaptive Boosting) – Manual Implementation

## 📌 Overview

This project demonstrates AdaBoost by manually implementing the algorithm step-by-step. It includes weight initialization, model training, error calculation, weight updates, and final prediction using weighted voting.

---

## 🎯 What is AdaBoost?

AdaBoost is a boosting technique that improves model performance by:

* Training models sequentially
* Increasing focus on misclassified data points
* Assigning weights to both data points and models
* Combining weak learners into a strong classifier

---

## 🎯 Objective

* Understand AdaBoost mathematically
* Implement weight updates manually
* Train multiple weak learners
* Combine predictions using weighted voting

---

## 📂 Dataset

* Small custom dataset with 2 features
* Used for visualization and understanding boosting behavior

---

## 🔍 Steps Performed

* Data Visualization
* Initial Weight Assignment
* Weak Learner Training (Decision Stumps)
* Error Calculation
* Model Weight (Alpha) Calculation
* Weight Update
* Resampling
* Final Prediction

---

## 📊 Results

* Model performance improved across iterations
* Misclassified points were given higher importance
* Final prediction combined multiple weak learners effectively

---

## 🖼️ Visualization

* First Dataset
<img width="515" height="389" alt="image" src="https://github.com/user-attachments/assets/46e21990-bde0-4508-9f3a-fe144f91676f" />

* Resampled Dataset

<img width="515" height="389" alt="image" src="https://github.com/user-attachments/assets/30b5fa88-ccf0-445a-9691-d9602fd8dc3d" />



---

## 🛠 Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* mlxtend

---

## 🚀 Future Improvements

* Use larger datasets
* Compare with Random Forest
* Tune number of estimators

---
