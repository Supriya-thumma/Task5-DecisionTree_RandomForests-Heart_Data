# 🌳 Task 5 - Decision Trees & Random Forests

This project is part of my AI & ML Internship Task 5 by Elevate Labs. It implements **Decision Tree** and **Random Forest** models to classify heart disease presence based on patient health metrics.  
The task focuses on understanding tree-based algorithms, handling overfitting, interpreting feature importance, and evaluating models using cross-validation.

---

## 📌 Project Overview
- **Dataset**: Heart Disease Dataset (`heart.csv`)
- **Objective**: Learn tree-based models for classification & regression
- **Tools Used**: Python, Pandas, Scikit-learn, Matplotlib, Seaborn, Graphviz
- **Key Learnings**:
  - Decision Tree training & visualization
  - Overfitting control with `max_depth`
  - Random Forest training & comparison
  - Feature importance interpretation
  - Cross-validation evaluation

---

## 📊 Results
| Model                                | Accuracy | Key Notes |
|--------------------------------------|----------|-----------|
| Decision Tree                        | 98.54%   | High accuracy, prone to overfitting |
| Decision Tree (max_depth=4)          | 80.00%   | Reduced overfitting, but lower accuracy |
| Random Forest                        | 98.54%   | Balanced performance & generalization |
| Random Forest Cross-Validation (CV)  | 99.71%   | Strong model stability |

---

## 📦 Requirements
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `graphviz`
