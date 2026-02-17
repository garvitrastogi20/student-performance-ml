# 📊 Student Math Score Prediction using Machine Learning

## 📌 Overview
This project predicts students' math scores using machine learning regression models. Multiple algorithms were evaluated and compared to determine the best-performing model based on cross-validation metrics.

The project demonstrates model comparison, performance evaluation, and selection of the optimal regression algorithm.

---

## 🎯 Objective
To predict students' math scores based on academic features using regression techniques and identify the best-performing model.

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- Kaggle Dataset

---

## 📂 Dataset
The dataset contains student academic information including weekly self-study hours and corresponding math scores.

Target Variable:
- `math_score`

Feature Used:
- `weekly_self_study_hours`

Dataset Source:
Kaggle – Student Scores Dataset

---

## ⚙️ Machine Learning Models Evaluated

The following regression models were compared using 5-fold cross-validation:

- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor
- LightGBM Regressor

---

## 📊 Evaluation Metrics

Models were evaluated using:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- R² Score (Coefficient of Determination)

The best model was selected based on lowest RMSE.

---

## 🏆 Model Selection Strategy

1. Performed 5-fold cross-validation on training data
2. Calculated RMSE, MAE, and R² for each model
3. Selected the model with lowest average RMSE
4. Evaluated final performance on validation set

---

## 📈 Validation Performance

Final model performance was evaluated on a hold-out validation set using:

- RMSE
- MAE
- R² Score

(Replace this section with your actual results)

Example:

- RMSE: 4.82
- MAE: 3.91
- R² Score: 0.87

---


## 🚀 Future Improvements

- Hyperparameter tuning
- Feature engineering with additional academic attributes
- Model deployment using Flask or Streamlit
- Compare deep learning regression models

---

## 👨‍💻 Author

Garvit Rastogi  
Computer Science Undergraduate  
Interested in Machine Learning and Full-Stack Development
