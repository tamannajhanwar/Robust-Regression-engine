# 🏡 House Price Prediction Using Regression Models

## 📌 Project Overview
This project focuses on predicting house prices using different Machine Learning regression algorithms. It explores Linear Models, Tree-Based Models, and Support Vector Regression (SVR) to compare their performance and understand which model works best for the dataset.

## 🎯 Project Objectives
- Understand and prepare the dataset.
- Perform data preprocessing and feature scaling.
- Implement different regression algorithms.
- Apply cross-validation techniques.
- Compare model performance using evaluation metrics.
- Identify the best-performing regression model.

## 📂 Models Implemented

### 1. Linear Models
- Ridge Regression
- Lasso Regression

### 2. Tree-Based Models
- Decision Tree Regressor
- Random Forest Regressor

### 3. Support Vector Regression
- Linear Kernel
- Polynomial Kernel
- RBF Kernel

## 🔄 Data Preprocessing
- Data loading and inspection using Pandas.
- Handling date columns.
- Separating independent and dependent variables.
- Train-test splitting (80:20).
- Feature scaling using StandardScaler.

## 📊 Cross-Validation Techniques
- K-Fold Cross-Validation
- Stratified K-Fold
- Leave-One-Out Cross-Validation (LOOCV)
- Time Series Split

## 📈 Model Evaluation Metrics
- **MAE:** Mean Absolute Error
- **MSE:** Mean Squared Error
- **RMSE:** Root Mean Squared Error
- **R² Score:** Measures the explanatory power of the model.

## 🏆 Model Performance Comparison

| Model | R² Score |
|---|---:|
| Ridge Regression | 0.9187 |
| Lasso Regression | 0.9187 |
| Decision Tree | 0.8835 |
| Random Forest | 0.9275 |
| SVR (RBF) | 0.0265 |

**Key Observation:** Random Forest achieved the highest R² score, followed by Ridge and Lasso Regression. SVR showed comparatively poor performance.

*Note: These are the approximate scores reported in the notebook's earlier comparison. Final results should be verified after correcting evaluation inconsistencies.*

## 🛠️ Technologies & Libraries Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## ▶️ How to Run This Project

1. Clone this repository.
2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

3. Add the dataset to your project folder.
4. Open the Jupyter Notebook.
5. Update the dataset path if required.
6. Run all cells.

## 📁 Project Structure

```text
House-Price-Prediction/
│
├── pr2.ipynb
├── README.md
└── dataset.csv
```

## 💡 Conclusion
This project helped explore different regression algorithms and understand their working principles and performance.

Random Forest demonstrated the best performance among the compared models, while Ridge and Lasso also achieved strong results. The project highlights the importance of model selection, feature scaling, cross-validation, and performance evaluation in Machine Learning.

---
✨ **Created as a Machine Learning Regression Project.**
