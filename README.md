# Linear Regression Model

This project demonstrates the implementation of a Linear Regression model to predict **housing prices** based on a variety of features such as the number of rooms, location, and square footage. The model is built using Python libraries, and various techniques like feature selection, regularization (Lasso), and model evaluation are demonstrated.


## Project Overview

The project uses a dataset to train and test the performance of a Linear Regression model. It also includes an exploration of feature selection and regularization using the Lasso method to potentially improve the model's performance. The project's goals include:

- Fitting a Linear Regression model.
- Testing performance on a held-out test dataset.
- Implementing Lasso regularization to reduce overfitting.
- Evaluating the model performance using metrics like Mean Squared Error (MSE) and R-squared.

## Dataset

The dataset used is loaded and preprocessed within the notebook. It contains multiple features that are used to predict a continuous target variable.

## Models Implemented

1. **Simple Linear Regression**:
   - A basic linear model is trained on the dataset using a subset of features.
   - The model is evaluated using MSE and R-squared metrics.

2. **Lasso Regularization**:
   - Lasso (Least Absolute Shrinkage and Selection Operator) is applied to the model to handle feature selection and reduce model complexity.
   - Cross-validation is used to determine the best regularization parameter (`alpha`).

## Evaluation

The performance of the models is evaluated using:

- **Mean Squared Error (MSE)**: Measures the average of the squares of the errors between predicted and actual values.
- **R-squared (R²)**: Provides the proportion of the variance in the dependent variable that is predictable from the independent variables.

### Model Performance

- **Best alpha for Lasso Regularization**: 0.001 (as determined by cross-validation)
- **Linear Regression MSE**: 24.99
- **Linear Regression R²**: 0.659

## How to Run the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/linear-regression-model.git

## Conclusion

While the model performs decently with a **R² of 0.659**, the results suggest there is room for improvement. Further enhancement could involve using larger datasets or experimenting with non-linear models like **Decision Trees** or **Random Forests**.

## Requirements

- **Python 3.x**
- **Libraries**:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
