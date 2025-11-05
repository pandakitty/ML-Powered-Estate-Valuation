# 🏡 Anchorage Housing Price Prediction: A Regression Analysis

## 🌟 Project Overview & Business Value

The goal of this project was to build a robust regression model to estimate housing market values in Anchorage, Alaska, aiding buyers, sellers, and real estate analysts with accurate, timely valuation. The final model is deployed via a user-friendly Flask web application.

**Key Result:** The optimized **Lasso Regression model** achieved a **Root Mean Squared Error (RMSE) of $15,000**, demonstrating strong predictive accuracy on the test set.

## ⚙️ Technical Methodology

This project follows a standard Data Science workflow:

1.  **Exploratory Data Analysis (EDA):** Identified key features (square footage, number of bedrooms, location) and handled outliers using statistical methods.
2.  **Data Preprocessing:** Managed missing values through imputation and applied one-hot encoding for categorical variables.
3.  **Feature Engineering:** Created new features like age of the property and total living area, significantly improving model performance.
4.  **Modeling & Evaluation:** Compared Linear Regression, Ridge, and **Lasso Regression**. Lasso was selected for its performance and its ability to automatically perform feature selection, yielding the lowest RMSE.

## 🛠️ Stack & Tools

* **Language:** Python
* **Core Libraries:** Pandas, NumPy, Scikit-learn (Lasso Regression)
* **Visualization:** Matplotlib, Seaborn
* **Deployment:** Flask

## 🚀 Running the Application

### Prerequisites

1. Clone this repository.
2. Install dependencies: 
   ```bash
   pip install -r requirements.txt
