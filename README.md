# 🧠 Autism Detection Using ML

This project applies machine learning techniques to predict Autism Spectrum Disorder (ASD) in adults using behavioral and demographic data. We explored multiple models including logistic regression, decision tree, SVM, and artificial neural networks to evaluate classification performance.

## 👥 Collaboration

This project was collaboratively built by our team members:

- [Nushrat Jaben Aurnima](https://github.com/NushratJabenAurnima)  
- [Zihad Khan](https://github.com/Zihad107)  
- [Shairin Akter Hashi](https://github.com/Shairin207)  
- [MD Shahrukh Hossain Shihab](https://github.com/shihab372)

> _Thanks to everyone for their dedication and effort._

---

## 📌 Project Overview

This project was submitted as part of the **CSE 366 – Machine Learning** course. It involves:

- Collecting and preparing a publicly available dataset
- Performing data preprocessing and exploratory data analysis (EDA)
- Training multiple machine learning models to classify ASD
- Comparing model performance and drawing conclusions

---

## 📊 Dataset Information

- **Source**: [Kaggle – Autism Screening on Adults](https://www.kaggle.com/datasets/andrewmvd/autism-screening-on-adults)  
- **Total Instances**: 704 rows  
- **Total Features**: 21  
- **Target Variable**: `Class/ASD` (1 = Autism, 0 = No Autism)

---

## 🚀 Key Features

### 🔹 **Data Preprocessing**
- Renamed inconsistent column names
- Encoded categorical variables using Label Encoding
- Replaced missing values and dropped irrelevant columns

### 🔹 **Exploratory Data Analysis (EDA)**
- Correlation Matrix to analyze feature relationships
- Histograms and Bar Plots to understand age and ethnic distributions

### 🔹 **Model Training**
- Split data (80% Train, 20% Test)
- Models used:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Decision Tree
  - Artificial Neural Network (ANN)

### 🔹 **Performance Evaluation**
- Metrics: Accuracy, Precision, Recall, F1-Score
- Confusion Matrices for each model
- Comparative analysis between traditional models and ANN

---

## 🧠 Model Performance Summary

| Model                | Accuracy | Remarks                             |
|---------------------|----------|-------------------------------------|
| Logistic Regression | 100%     | Overfit on test data                |
| SVM (Linear)        | 100%     | Overfit on test data                |
| Decision Tree       | 100%     | Risk of memorization                |
| ANN (Neural Net)    | 93%      | Best generalization & realistic     |

---

## 🧪 System Modules

| Module             | Description |
|-------------------|-------------|
| **Preprocessing** | Data cleaning, encoding, and splitting |
| **EDA**           | Visualization and correlation study |
| **ML Models**     | Logistic Regression, SVM, Decision Tree, ANN |
| **Evaluation**    | Confusion matrix, Accuracy, Precision, F1-score |

---

## 🛠 Technologies Used

- **Language**: Python  
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras  
- **Notebook**: Jupyter (`.ipynb`)

---

## ⚠️ Limitations

- Small dataset size may not generalize well
- No cross-validation used (only single train-test split)
- Class imbalance and duplicates not addressed
- ROC, AUC, and advanced metrics not explored

---

## 💡 Future Enhancements

- Introduce k-fold cross-validation
- Handle class imbalance using SMOTE
- Check for and remove duplicates
- Use ensemble models like Random Forest or XGBoost
- Analyze AUC-ROC and precision-recall curves
