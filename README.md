# F1stToLeave – Churn Prediction Model Project

This project addresses a **customer churn classification problem** using an end-to-end supervised machine learning pipeline. The process includes:

- Comprehensive **data preprocessing** (handling missing values, encoding categorical features, scaling numericals)
- **Class balancing** to address target imbalance
- **Model comparison** across multiple algorithms
- **Hyperparameter tuning** to optimize performance
- **Feature importance analysis** for interpretability

The primary objective is to build a robust model that accurately predicts which customers are at risk of churning, with a strong focus on optimizing the **F1 Score** — a metric that balances precision and recall, especially important in imbalanced classification tasks.

---

## File Language Notice

- The **notebook (`.ipynb`)** and the **project brief (`instructions.pdf`)** are written in **Spanish**, as this project was originally developed for a Spanish-language context.
- All code is fully annotated and structured for easy understanding, regardless of language.

---

## Project Files

| File                                          | Description                                                             |
|-----------------------------------------------|-------------------------------------------------------------------------|
| `F1stToLeave_churn_prediction_model_project.ipynb` | Main notebook: preprocessing, model training, evaluation, and predictions. *(Spanish)* |
| `churn_train.csv`                             | Training dataset with features and churn labels.                        |
| `churn_predict.csv`                           | Unlabeled dataset used to generate churn predictions.                   |
| `instructions.pdf`                            | Project description and requirements. *(Spanish)*                       |
| `predictions.csv`                             | Final churn predictions for the test dataset.                           |
| `README.md`                                   | This file.                                                              |

---

## 🛠Tools & Libraries

- Python 3
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn  
- imbalanced-learn  
- xgboost, catboost  
- shap  
