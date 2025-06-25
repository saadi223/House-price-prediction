# House price prediction
#  House Price Prediction Using Machine Learning

This project demonstrates how to predict house prices using various regression algorithms including **Linear Regression**, **Ridge**, and **Lasso**, trained on real-world housing data.


##  Dataset Overview

- Features: Area, bedrooms, bathrooms, floors, etc.
- Target: **House Sale Price**
- Format: `.csv` file (loaded as `house.csv`)
- Source: Uploaded manually or from Kaggle datasets



## Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Gradio (for web deployment)


##  Models Trained & Compared

| Model              | R² Score | Mean Squared Error |
|-------------------|----------|---------------------|
| Linear Regression | ~0.91    |  Good baseline     |
| Ridge Regression  | ~0.92    |  Improved accuracy |
| Lasso Regression  | ~0.89    |  Slight underfit   |

**Ridge Regression performed best** due to effective regularization.

##  Model Evaluation

- R² Score
- Mean Squared Error (MSE)
- Actual vs Predicted plots
- Learning Curve analysis

###  Sample Learning Curve Plot

The learning curve helps diagnose:
- Underfitting
- Overfitting
- Generalization ability

##  Project Folder Structure

