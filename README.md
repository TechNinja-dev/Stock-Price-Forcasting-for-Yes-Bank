# 📈 Stock Price Prediction - Yes Bank 🏦

A comprehensive data science project that analyzes, models, and predicts the stock price of **Yes Bank** using historical data and machine learning techniques.

---

## 📌 Project Objective

To build a regression model that predicts the **closing stock price** of Yes Bank using technical features like Open, High, Low prices, and temporal attributes. The project also aims to provide insights through visualizations and model explainability tools.

---

## 🛠️ Key Features

- ✅ Cleaned and preprocessed real-world stock data
- 📊 Univariate, Bivariate, and Multivariate visual analysis
- 🧹 Outlier detection and handling using IQR
- 🔍 Feature selection based on domain relevance
- ⚙️ Models Implemented:
  - Linear Regression
  - Ridge Regression (with Hyperparameter Tuning)
  - Support Vector Regression (SVR)
- 🧪 Evaluation using MAE and R² Score
- 🔄 Cross-validation for robustness
- 💡 Model explainability using SHAP
- 💾 Saved the final model using `joblib` for deployment

---

## 🧪 Dataset Overview

- `Date`: Trading date
- `Open`, `High`, `Low`, `Close`: Stock prices
- `Month`, `Year`: Extracted time features
- `Daily_Return`, `Cumulative_Return`: Engineered features for trend analysis

---

## 📊 Evaluation Metrics

| Model             | MAE        | R² Score   |
|------------------|------------|------------|
| Linear Regression | ~3.73      | ~0.9915    |
| Ridge Regression  | ~3.73      | ~0.9914    |
| SVR (tuned)       | ~3.57      | ~0.9914    |

✅ Final Model Selected: **Tuned Support Vector Regression** due to better generalization and performance.

---

## 📁 Project Structure


├── Assignment.ipynb       # Main Jupyter Notebook
├── yesbank_model.pkl      # Saved model using Joblib
├── README.md              # Project overview
└── requirements.txt       # Required Python libraries (optional)

## 📬 Contact

Feel free to reach out if you have questions or feedback!

📧 Email: prakharsrivastava019@gmail.com
🔗Linked In https://www.linkedin.com/in/prakhar-srivastava-58bb85303?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app
