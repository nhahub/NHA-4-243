# 🚗 Car Price Prediction Using Machine Learning

A machine learning application that predicts the market price of a car based on its specifications. The project implements a complete end-to-end ML pipeline, including data preprocessing, feature engineering, model training, evaluation, and deployment using **Streamlit**.

---

## 📌 Project Overview

The objective of this project is to build an accurate and reliable car price prediction model using historical vehicle data. Several regression algorithms were trained and evaluated to determine the best-performing model.

The application allows users to enter vehicle specifications and instantly receive an estimated market price.

---

## 🌐 Live Demo

You can access the deployed application here:

**https://mlproject-6e69nc8mjuftnftrrtkdrs.streamlit.app/**

---

## ✨ Features

- Predict car prices using machine learning
- Data preprocessing and cleaning
- Outlier detection and treatment
- Feature engineering
- Label Encoding for categorical features
- Min-Max feature scaling
- Multiple regression models comparison
- Saved trained models using Joblib
- Interactive Streamlit web interface

---

## 📊 Dataset

The dataset contains information about used vehicles, including:

- Brand
- Model
- Manufacturing Year
- Mileage
- Fuel Type
- Transmission
- Engine Type
- Engine Power
- Engine Displacement
- Steering Wheel
- Body Type
- Region
- Number of Owners
- Vehicle Price (Target Variable)

---

## 🔧 Data Preprocessing

The preprocessing pipeline includes:

- Standardizing column names
- Handling missing values
- Removing duplicate records
- Feature selection
- Exploratory Data Analysis (EDA)
- Outlier detection using the IQR method
- Winsorization
- Chi-Square feature significance testing
- ANOVA statistical testing
- Label Encoding
- Min-Max Scaling

---

## 🤖 Machine Learning Models

The following regression algorithms were implemented:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic Net Regression
- Decision Tree Regressor
- Gradient Boosting Regressor

Hyperparameter tuning was performed using **RandomizedSearchCV** where applicable.

---

## 📈 Model Evaluation

Models were evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

### Final Model Performance

| Model | R² Score |
|--------|----------|
| Decision Tree Regressor | **0.9376** |
| Gradient Boosting Regressor | 0.9187 |
| Linear Regression | 0.7273 |
| Ridge Regression | 0.7273 |
| Lasso Regression | 0.7273 |
| Elastic Net Regression | 0.7273 |

The **Decision Tree Regressor** achieved the highest prediction accuracy and was selected as the final model.

---

## 💻 Technology Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Streamlit

---

## 📁 Project Structure

```
Car-Price-Prediction/
│
├── app.py
├── dataset.csv
├── best_model.pkl
├── label_encoders.pkl
├── minmax_scaler.pkl
├── columns.pkl
├── requirements.txt
├── README.md
└── notebooks/
```

---

## 🚀 Running the Project Locally

### 1. Clone the repository

```bash
git clone <repository-url>
cd Car-Price-Prediction
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the application

```bash
streamlit run app.py
```

---

## 📦 Saved Files

The project saves the following files for deployment:

- `best_model.pkl`
- `DecisionTree.pkl`
- `GradientBoosting.pkl`
- `LinearRegression.pkl`
- `Ridge.pkl`
- `Lasso.pkl`
- `ElasticNet.pkl`
- `label_encoders.pkl`
- `minmax_scaler.pkl`
- `columns.pkl`

---

## 🔮 Future Improvements

- Integrate XGBoost and LightGBM
- Add Deep Learning models
- Include economic and temporal factors
- Automate model retraining
- Enhance feature engineering
- Improve UI/UX
- Add user authentication and prediction history

---

## 👨‍💻 Authors

Machine Learning Project

Developed as part of the Machine Learning course.

---

## 📄 License

This project is intended for educational purposes.
