# ❤️ Heart Disease Prediction (Bagging XGBoost)

## 📌 Overview
This project predicts whether a patient has heart disease using a **Bagging Ensemble with XGBoost**. 
The model is tuned to prioritize **Recall** (minimizing False Negatives) to ensure sick patients are not misdiagnosed as healthy.

## 🚀 Key Features
- **Data Preprocessing:** Handled missing values, scaling, and categorical encoding.
- **Exploratory Data Analysis (EDA):** Correlation heatmaps and feature distribution analysis.
- **Model Architecture:** BaggingClassifier wrapping an XGBoostClassifier.
- **Performance:** Achieved **84.3% Accuracy** with high sensitivity for at-risk patients.

## 🛠️ Tech Stack
- Python
- Scikit-Learn
- XGBoost
- Pandas & NumPy
- Matplotlib & Seaborn

## 📊 Results & Performance
The model was evaluated using a weighted approach (`scale_pos_weight=3`) to penalize missing sick cases.

| Metric | Score |
| :--- | :--- |
| **Accuracy** | 84.3% |
| **Recall (Sick)** | 91% |
| **Precision** | 84% |

**Confusion Matrix:**
![Confusion Matrix](path_to_your_confusion_matrix_image.png)
*(Add your confusion matrix screenshot here)*
