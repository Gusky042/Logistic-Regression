# Titanic Survival Prediction using Decision Tree

## 📋 Project Overview
Predicts whether a passenger survived the Titanic disaster based on features like age, gender, passenger class, and family size.

**Dataset:** Titanic (891 passengers, 12 features)

**Goal:** Binary classification (0 = Died, 1 = Survived)

---

## 🎯 Results
| Metric | Score |
|--------|-------|
| Accuracy | 81.6% |
| ROC-AUC | 0.838 |

**Best Model:** Random Forest (max_depth=5)

---

## 📊 Key Findings
- **Top features:**
  1. Sex (female = higher survival)
  2. Passenger class (1st class = higher survival)
  3. Age (children = higher survival)

- **Insight:** "Women and children first" pattern is clearly visible in the data

---

## 🛠️ Data Processing
- Handled missing Age values (filled with median)
- Created family_size feature (SibSp + Parch + 1)
- Converted Sex to numeric (male=0, female=1)

---



## 🚀 How to Run
```bash
git clone https://github.com/Gusky042/Decision-Tree.git
pip install -r requirements.txt
jupyter notebook notebooks/titanic_decision_tree.ipynb
---
## 💡 What I Learned
Handling missing values in real datasets

Converting categorical features to numeric

Feature engineering (family_size)

Decision tree visualization

## 👤 Author
**Gusky042**

GitHub: https://github.com/Gusky042

LinkedIn: [Your LinkedIn URL]

## 📅 Project Timeline
Started: April 2026

Last Updated: April 2026
