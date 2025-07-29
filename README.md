# 🩺 Diabetes Prediction using K-Nearest Neighbors (KNN)

This repository contains my solution for [Diabetes Prediction – Kaggle](https://www.kaggle.com/datasets/saurabh00007/diabetescsv) competition.
This project aims to predict whether a person has diabetes using the Pima Indians Diabetes dataset. 
The model uses the **K-Nearest Neighbors (KNN)** algorithm.

---

## 🗂️ Project Structure

```

├── 📊 diabetes.csv              # Dataset file
├── 📄 diabetes_task.ipynb       # Jupyter notebook with EDA, preprocessing, modeling
└── 📜 README.md                 # Project documentation (this file)

```

---

## 💻 Technologies Used

- **Language**: Python 3.x  
- **Environment**: Jupyter Notebook


## 📦 Libraries

- `pandas`, `numpy` – Data manipulation  
- `matplotlib`, `seaborn` – Visualization  
- `scikit-learn` – Preprocessing & modeling (`KNeighborsClassifier`, `classification_report`, `confusion_matrix`)  
- `GridSearchCV` – Hyperparameter tuning  
- `warnings` – Suppress warnings

---

## 🧠 Modeling

- Applied **K-Nearest Neighbors** classifier.
- Optimized `k` hyperparameter with cross-validation.
- Used an 80/20 train-test split.
- Achieved **82% accuracy** on the test set.

---

## 📈 Evaluation Metrics

| Metric      | Score |
|-------------|-------|
| Accuracy    | 82%   |
| Precision   | 0.77  |
| Recall      | 0.82  |
| F1-Score    | 0.79  |

---

## ⚙️ Installation

To install all required libraries:

