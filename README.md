# Simple Linear Regression Using SGDRegressor

## Project Overview
This project implements Simple Linear Regression using the `SGDRegressor` model from Scikit-learn. The goal is to learn the relationship between an input feature and a continuous output using the equation \(y = mx + c\).

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

## Dataset
A synthetic dataset containing 1,000 samples was generated using the equation:

`y = 4x + 3`

- Original coefficient (slope): 4
- Original intercept: 3

## Model
`SGDRegressor` was used to train the regression model using Stochastic Gradient Descent.

## Model Parameters
The trained model learned the following approximate values:

- Learned coefficient: 3.9646
- Learned intercept: 3.0423

## Prediction
The trained model was used to predict an output for a new input value.

For `x = 1`, the predicted output was approximately `7.007`.

## Model Evaluation
The model was evaluated using Mean Squared Error (MSE) and Root Mean Squared Error (RMSE).

- MSE: 0.00047219
- RMSE: 0.02173

## Parameter Error
The learned parameters were compared with the original parameters:

- Absolute coefficient error: approximately 0.03536
- Absolute intercept error: approximately 0.04232

## Conclusion
The `SGDRegressor` model learned coefficient and intercept values close to the original parameters. The low MSE and RMSE indicate that the model's predictions are close to the actual output values for this synthetic dataset.

## Future Improvements
- Visualize the original data and learned regression line.
- Experiment with different learning rates and training settings.
- Explore polynomial regression using a quadratic equation.
