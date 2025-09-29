Crocodile Length Prediction
Project Overview

This project aims to predict the length of crocodiles using various features such as weight, age, sex, and other available attributes. It demonstrates the use of supervised regression techniques including Linear and Polynomial Regression, with visualization and evaluation of model performance.

Dataset

The dataset contains measurements and attributes of crocodiles.

Features include:

weight

age

sex

…and other relevant features.

Target variable:

length (continuous)

Methodology

Data Exploration & Preprocessing

Checked for missing values and basic statistics

Selected relevant features

Modeling

Linear Regression as baseline

Polynomial Regression for capturing non-linear relationships

Random Forest Regression (optional for comparison)

Model Evaluation

Metrics: Mean Squared Error (MSE), R² Score

Cross-validation for stability

Visualization

Actual vs Predicted scatter plots

Polynomial regression curve

Residual plots

Feature vs Target scatter plots

Results

Linear Regression:

MSE ≈ 0.33

R² ≈ 0.71

Polynomial Regression:

MSE ≈ 0.16

R² ≈ 0.86

Polynomial Regression outperformed Linear Regression, capturing non-linear relationships between features and crocodile length.

How to Run

Clone the repository:

git clone https://github.com/yourusername/Crocodile_Prediction_Model.git


Open the Jupyter Notebook (Crocodile_Length_Prediction.ipynb)

Install required libraries if not already installed:

pip install pandas numpy matplotlib scikit-learn


Run the notebook step-by-step to train models, visualize results, and evaluate performance.

Insights

Features like weight and age are strong predictors of length.

Polynomial Regression can model non-linear relationships effectively.

Outliers in the dataset can affect model performance (visualized via residual plots).

Author

Ashish Ranjan

GitHub: https://github.com/theashishsaga
