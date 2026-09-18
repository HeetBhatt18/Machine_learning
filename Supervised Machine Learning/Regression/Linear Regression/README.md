# 🚗 Car Purchase Amount Prediction using Linear Regression

A Machine Learning project that uses **Linear Regression** to predict the amount a customer is likely to spend on purchasing a car based on customer-related features.

## 📌 Project Overview

This project demonstrates the implementation of a **Linear Regression model** as part of supervised machine learning.

The goal is to understand the relationship between customer attributes and their **car purchase amount**, then use those relationships to make predictions for new customers.

The project covers the basic Machine Learning workflow:

* Data loading
* Data exploration
* Data preprocessing
* Feature selection
* Train-test splitting
* Model training
* Prediction
* Model evaluation
* Data visualization

## 🎯 Objective

The main objective of this project is to build a Linear Regression model that can predict the **car purchase amount** based on customer information.

This project is also intended to provide practical experience with the complete workflow of a supervised regression problem.

## 📊 Dataset

The dataset contains customer information along with their car purchase amount.

Typical attributes include:

| Feature             | Description                                          |
| ------------------- | ---------------------------------------------------- |
| `Gender`            | Gender of the customer                               |
| `Age`               | Age of the customer                                  |
| `AnnualSalary`      | Customer's annual salary                             |
| `CreditCardDebt`    | Customer's credit card debt                          |
| `NetWorth`          | Estimated net worth of the customer                  |
| `CarPurchaseAmount` | Target variable representing the car purchase amount |

> The exact columns used by the model depend on the preprocessing and feature-selection steps implemented in the project notebook/script.

## 🧠 Machine Learning Algorithm

### Linear Regression

Linear Regression is a supervised learning algorithm used for predicting a **continuous numerical value**.

The general equation is:

```text
y = b₀ + b₁x₁ + b₂x₂ + ... + bₙxₙ
```

Where:

* `y` → predicted value
* `b₀` → intercept
* `b₁ ... bₙ` → model coefficients
* `x₁ ... xₙ` → input features

In this project, the model learns the relationship between customer attributes and the **Car Purchase Amount**.

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Preprocessing
   ↓
Feature Selection
   ↓
Train-Test Split
   ↓
Linear Regression Model
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

## 🛠️ Technologies Used

* **Python**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Scikit-learn**
* **Jupyter Notebook / VS Code**

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/HeetBhatt18/Machine_learning.git
```

Navigate to the project directory:

```bash
cd Machine_learning/Supervised\ Machine\ Learning/Regression/Linear\ Regression/Car_Purchase
```

Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## ▶️ How to Run

1. Clone the repository.
2. Open the `Car_Purchase` folder in VS Code or Jupyter Notebook.
3. Make sure the dataset path is correctly configured.
4. Install the required Python libraries.
5. Run the Python notebook/script step by step.
6. Observe the model predictions and evaluation results.

## 📈 Model Evaluation

The Linear Regression model can be evaluated using common regression metrics such as:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

Represents the square root of MSE and provides the error in the same unit as the target variable.

### R² Score

Measures how well the model explains the variation in the target variable.

```python
from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score

mae = mean_absolute_error(y_test, y_pred)
mse = mean_squared_error(y_test, y_pred)
rmse = mean_squared_error(y_test, y_pred) ** 0.5
r2 = r2_score(y_test, y_pred)

print("MAE:", mae)
print("MSE:", mse)
print("RMSE:", rmse)
print("R² Score:", r2)
```

## 📉 Visualization

The project can use visualizations to understand the relationship between:

* Customer age and purchase amount
* Annual salary and purchase amount
* Net worth and purchase amount
* Actual vs predicted purchase amounts

An **Actual vs Predicted** plot can also be used to visually evaluate the performance of the regression model.

## 📁 Project Structure

```text
Car_Purchase/
│
├── car_purchasing.csv
├── Linear_Regression.ipynb
└── README.md
```

> File names may differ depending on the current files in the project folder.

## 💡 Key Learning Outcomes

Through this project, I practiced:

* Understanding supervised learning
* Understanding regression problems
* Loading datasets using Pandas
* Exploring datasets
* Preparing data for Machine Learning
* Splitting data into training and testing sets
* Implementing Linear Regression using Scikit-learn
* Making predictions
* Evaluating regression models
* Visualizing Machine Learning results

## 🚀 Future Improvements

Possible improvements for this project include:

* Implementing **Multiple Linear Regression**
* Comparing Linear Regression with other regression algorithms
* Applying feature scaling where appropriate
* Performing more detailed exploratory data analysis
* Hyperparameter/model comparison
* Building a simple prediction interface
* Deploying the model as a web application

## 👨‍💻 Author

**Heet Bhatt**

BCA Student | AI & ML Learner

GitHub: [HeetBhatt18](https://github.com/HeetBhatt18)

---

⭐ If you found this project useful, feel free to explore the other Machine Learning projects in the repository.
