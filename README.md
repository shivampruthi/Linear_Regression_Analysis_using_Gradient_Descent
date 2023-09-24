# Linear_Regression_Analysis_using_Gradient_Descent

This repository contains Python code for performing stock market analysis using linear regression. The project involves utilizing the gradient descent optimization technique to improve the linear regression model's accuracy and predict stock prices based on relevant features.

## Overview

The main objective of this project is to implement linear regression using gradient descent for analyzing stock market data. The dataset used (`data.csv`) comprises two columns: one representing relevant features related to the stock market (e.g., time, trading volume) and the other representing the corresponding stock prices.

## Contents

- `stock_market_analysis.ipynb`: Jupyter Notebook containing the code for implementing linear regression using gradient descent and evaluating the model's performance.
- `data.csv`: Dataset used for the analysis, containing two columns representing the input feature and target variable.

## Implementation Details

- `step_gradient(points, learning_rate, m, c)`: Function to perform a single step of gradient descent and update the model parameters (slope and intercept).
- `gd(points, learning_rate, num_iterations)`: Function to execute the gradient descent algorithm and optimize the linear regression model.
- `cost(points, m, c)`: Function to calculate the cost of the model based on the provided dataset.

## How to Use

1. Ensure you have Python and the necessary libraries (NumPy) installed.
2. Clone this repository to your local machine.
3. Open the Jupyter Notebook `stock_market_analysis.ipynb` and run the cells to see the implementation of linear regression using gradient descent and its evaluation.

## Results

The gradient descent algorithm significantly improved the model's accuracy, leading to a notable reduction in the cost function. The final optimal slope (m) was approximately 1.479, and the intercept (c) was around 0.030. These optimized model parameters indicate a better fit to the stock market data, allowing for more accurate predictions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute or report issues in this repository.
