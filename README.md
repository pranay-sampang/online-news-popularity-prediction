# Online News Popularity Prediction

## Project Overview
This project predicts the popularity of online news articles based on the number of shares on social media. Using the Online News Popularity dataset, the project applies machine learning techniques to identify key factors that influence article virality and build accurate prediction models.

---

## Objectives
- To analyse and preprocess the Online News Popularity dataset
- To perform exploratory data analysis to identify and understand patterns, relationships, and anomalies
- To perform feature engineering and data transformation
- To implement baseline regression models and ensemble-based machine learning methods such as Random Forest, Gradient Boosting, and XGBoost
- To evaluate and compare model performance using metrics such as RMSE, MAE, and R²

---

## Project Structure
```
online-news-popularity-prediction/
│
├── data/
│   └── OnlineNewsPopularity.csv    # Dataset
|
├── figures/                        # Figures
|
├── models/                         # Saved best model
│
├── notebooks/
│   ├── data_cleaning.ipynb       # Data preprocessing and cleaning
│   ├── data_exploration.ipynb    # Exploratory data analysis
│   ├── feature_engineering.ipynb # Feature selection and transformation
│   └── model_building.ipynb      # Model training and evaluation
│
└── README.md                       # Project documentation
```

---

## Dataset
The dataset used is the [Online News Popularity Dataset](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity) from the UCI Machine Learning Repository. It contains 39,644 articles from Mashable with 61 features including content-based, keyword-based, and social features.

- **Target variable:** `shares` — number of times an article was shared on social media

---

## Technologies Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Models Used
| Model | Type |
|---|---|
| Dummy (mean) | Baseline |
| Linear Regression | Linear |
| Ridge (α = 1.0)  | Linear |
| Lasso (α = 0.01) | Linear |
| Random Forest | Ensemble |
| Gradient Boosting | Ensemble |
| XGBoost | Ensemble |
| LightGBM | Ensemble |
| LightGBM (Optuna) | Ensemble |

---

## Evaluation Metrics
- **RMSE** — Root Mean Squared Error
- **MAE** — Mean Absolute Error
- **R²** — Coefficient of Determination
