# Multilinear-Regression-Model-

# Car Price Prediction - Multilinear Regression

## 📌 Project Overview
This project implements a professional end-to-end Machine Learning pipeline to predict car prices. Using a dataset containing features such as manufacturing year, cylinder count, and mileage, I developed a Multilinear Regression model that explains nearly all variance in the target variable.

## 🚀 Key Features
- **Data Cleaning:** Handled missing values (NaN) in the `Cylinder` column by imputing logic-based values.
- **Model Training:** Utilized `sklearn.linear_model.LinearRegression` for high-precision modeling.
- **Mathematical Verification:** Manually validated the model's coefficients and intercept by calculating the regression equation $(Y = m_1x_1 + m_2x_2 + m_3x_3 + b)$ to ensure prediction accuracy.
- **Persistence:** Implemented model serialization using both `pickle` and `joblib` for deployment readiness.
- **Evaluation:** Achieved a near-perfect **R² score of 99.8%**.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Joblib, Pickle
- **Environment:** Google Colab / Jupyter Notebooks

## 📊 Model Performance
- **R² Accuracy:** 0.99804
- **Verified Prediction:** A 2021 car with 6 cylinders and 170k mileage was predicted at approximately **$13,721.08**.

## 📂 Repository Structure
- `car_price_analysis.ipynb`: The main notebook containing data cleaning, training, and verification.
- `models/`: Directory containing the saved `.pickle` and `.joblib` files.

## 📝 How to Use
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy scikit-learn joblib`.
3. Run the notebook to see the mathematical verification and performance metrics.
```
