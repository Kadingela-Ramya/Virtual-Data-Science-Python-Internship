# Week 4: Machine Learning Model Development and Evaluation

## 📌 Project Overview

This project was completed as part of my Virtual Data Science with Python Apprentice Internship. The objective of this task was to build, train, evaluate, and compare basic machine learning classification models using Python.

The Breast Cancer dataset from Scikit-learn was used for this project. The goal was to predict whether a tumor belongs to the malignant or benign class based on multiple numerical features.

---

## 📊 Dataset

The dataset was loaded directly using Scikit-learn.

Target classes:

- 0 – Malignant
- 1 – Benign

The dataset contains multiple numerical features related to tumor characteristics.

---

## 🔄 Project Workflow

The following steps were performed:

1. Loaded and explored the dataset
2. Checked for missing values and duplicate records
3. Examined the target class distribution
4. Separated features and target variables
5. Split the data into training and testing sets
6. Applied feature scaling
7. Trained machine learning models
8. Evaluated model performance
9. Compared the results

---

## 🤖 Machine Learning Models

Two classification models were developed:

### Logistic Regression

Logistic Regression was used as a baseline model for binary classification. Feature scaling was applied before training.

### Decision Tree Classifier

A Decision Tree model was trained to capture possible non-linear relationships between the features and target variable.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- AUC Score

---

## 📊 Visualizations

The project includes the following visualizations:

1. Target Class Distribution
2. Logistic Regression Confusion Matrix
3. Decision Tree Confusion Matrix
4. ROC Curve Comparison
5. Model Accuracy Comparison

---

## ⚠️ Model Limitations

Possible sources of error include dataset limitations, train-test split variation, model hyperparameters, and potential overfitting. Future improvements can include:

- Hyperparameter tuning
- Cross-validation
- Feature selection
- Decision Tree pruning
- Testing additional machine learning models

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

## 📂 Project Files

- `Week4_Machine_Learning_Model.ipynb` – Complete machine learning implementation
- `Week4_Machine_Learning_Model_Report.pdf` – Project documentation
- `README.md` – Project overview and documentation

---

## ✅ Conclusion

This project demonstrates the complete process of developing and evaluating machine learning models. Logistic Regression and Decision Tree models were trained and compared using multiple evaluation metrics and visualizations. The project helped in understanding data preprocessing, model training, prediction, performance evaluation, and model comparison using Python.
