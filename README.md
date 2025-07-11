# Titanic-Survival-Prediction
# 🚢 Titanic Survival Prediction using ML

This project uses machine learning (Logistic Regression and Random Forest) to predict passenger survival in the Titanic dataset.

## 📊 Dataset

- Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- Features: Passenger info (age, sex, fare, class, family size, etc.)

## 🧹 EDA & Preprocessing

- Handled missing values manually and with median imputation
- Engineered features like `FamilySize`
- Encoded categorical variables (`sex`, `embarked`, `who`, etc.)

## 🤖 Models Used

| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | 80.4%    |
| Random Forest       | 81.6%    |

## 🔍 Insights

- Gender (`sex`) and `pclass` were strong predictors
- Random Forest showed slightly better performance
- No overfitting detected — models generalized well


## 🛠️ Tools Used

- Python (Pandas, Seaborn, Scikit-Learn)
- Jupyter Notebook
- Matplotlib for visualization
