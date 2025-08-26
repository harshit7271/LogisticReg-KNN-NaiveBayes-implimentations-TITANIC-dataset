# 🚢 Titanic Survival Prediction - Performance Evaluation with ML

This project implements **Logistic Regression, K-Nearest Neighbors (KNN),Naive Bayes, Decision Trees and SVM** algorithms to predict passenger survival on the Titanic dataset.  
The dataset is sourced from the **Seaborn library** (`sns.load_dataset('titanic')`).  

The main objective is to **compare the performance of multiple classifiers** on the same dataset and evaluate them using accuracy, precision, recall, F1-score, and confusion matrices.


---

## ⚡ Features
- Loads Titanic dataset from **Seaborn**
- Preprocesses data (handles missing values, encoding categorical features)
- Implements **three ML models**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Gaussian Naive Bayes
  - Decision Tree Classifier
  - SVM (Support Vector Machine)
- Compares models based on:
  - ✅ Accuracy  
  - ✅ Precision, Recall, F1-score  
  - ✅ Confusion Matrix & Classification Reports
- Visualizes model performance

---

## 📊 Example Results
- Logistic Regression → ~0.81 accuracy  
- KNN → ~0.70 accuracy  
- Naive Bayes → ~0.77 accuracy  
- Decision Tree → ~0.78 accuracy
- SVM2  → ~0.82

*(Results may vary depending on preprocessing and hyperparameters.)*



