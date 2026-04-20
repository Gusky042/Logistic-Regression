# Breast Cancer Detection using Logistic Regression

## 📋 Project Overview
This project builds a machine learning model to predict whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** based on cell nucleus characteristics.

**Dataset:** Wisconsin Breast Cancer Database (569 samples, 30 features)

**Goal:** Classify tumors as Malignant (0) or Benign (1)

## 🎯 Results
| Metric | Score |
|--------|-------|
| Accuracy | 96.5% |
| Precision | 0.96 |
| Recall | 0.97 |
| F1-Score | 0.96 |
| ROC-AUC | 0.99 |

## 📊 Key Findings
- **Most important features:** Worst area, worst concave points, worst radius
- **Model type:** Logistic Regression with gradient descent from scratch
- **Key insight:** "Worst" measurements (largest values) are more predictive than mean measurements

## 🛠️ Technologies Used
- Python 3.13
- NumPy, Pandas, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
## 📁 Repository Structure
breast_cancer_project/
├── data/ # Dataset
├── notebooks/ # Jupyter notebooks
│ ├── 01_eda.ipynb # Exploratory Data Analysis
│ ├── 02_model.ipynb # Model training
│ └── 03_evaluation.ipynb # Results
├── models/ # Saved models
├── requirements.txt # Dependencies
└── README.md # This file

## 👤 Author

**Gusky042**

- GitHub: [https://github.com/Gusky042](https://github.com/Gusky042)

- Email: [paulchiagoziea@gmail.com]

---

## 📅 Project Timeline
- Started: April 2026
- Last Updated: April 2026

---

## 🙏 Acknowledgments
- Dataset: UCI Machine Learning Repository
- Mentor: Online AI/ML Course
