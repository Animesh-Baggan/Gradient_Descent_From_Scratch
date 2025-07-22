# Gradient Descent From Scratch

This Jupyter notebook demonstrates how to implement and visualize linear regression using both Ordinary Least Squares (OLS) and a manual, step-by-step approach to gradient descent for optimizing the intercept (bias) term. The workflow is educational and intended to help users understand the mechanics of gradient descent in the context of simple linear regression.

## Features
- Generates a synthetic regression dataset using scikit-learn
- Visualizes the data using matplotlib
- Fits a linear regression model using scikit-learn's OLS implementation
- Manually applies gradient descent to optimize the intercept (with a fixed slope)
- Visualizes the iterative updates to the regression line

## Workflow Summary
1. **Data Generation:**
   - Uses `make_regression` from scikit-learn to create a small dataset with noise.
2. **Visualization:**
   - Plots the generated data points.
3. **OLS Regression:**
   - Fits a linear regression model using scikit-learn and visualizes the result.
4. **Manual Gradient Descent:**
   - Initializes the slope and intercept.
   - Iteratively updates the intercept using the gradient of the loss function.
   - Visualizes the regression line after each update to show convergence.

## Requirements
- Python 3.x
- numpy
- matplotlib
- scikit-learn

You can install the required packages using:

```bash
pip install numpy matplotlib scikit-learn
```

## Usage
1. Open the notebook `Gradient_Descent_From_scratch.ipynb` in Jupyter Notebook or JupyterLab.
2. Run the cells sequentially to:
   - Generate and visualize data
   - Fit and plot the OLS regression line
   - Step through the gradient descent process and visualize each iteration

## Educational Value
This notebook is ideal for:
- Beginners learning about linear regression and gradient descent
- Visualizing how gradient descent updates model parameters
- Comparing manual optimization to library-based solutions

---

**Author:**
- [Your Name Here]

**License:**
- [Specify your license, e.g., MIT] 
