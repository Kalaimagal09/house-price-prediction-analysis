# house-price-prediction-analysis

House Price Prediction using Linear Regression 
🏠 This project implements a linear regression model to predict house prices based on various features. The primary goal is to understand and apply both simple (one feature) and multiple (many features) linear regression, evaluate the model's performance, and interpret its results.

## Project Workflow
The project follows a standard machine learning workflow from data preparation to model evaluation.

Data Preparation: The housing dataset was loaded using Pandas. For the initial analysis, a simple linear regression model was built using the area of the house as the single predictor variable and price as the target.

Train-Test Split: The dataset was split into an 80% training set and a 20% testing set to ensure the model could be evaluated on unseen data.

Model Training: A LinearRegression model from Scikit-learn was trained on the training data.

Model Evaluation: The model's performance was assessed using standard regression metrics:

R-squared (R²): Measures the proportion of the variance in the price that is predictable from the area.

Mean Absolute Error (MAE): The average absolute difference between the actual and predicted prices.

Mean Squared Error (MSE): The average of the squared differences between actual and predicted prices.

Visualization & Interpretation:

A scatter plot of area vs. price was created with the model's regression line overlaid to visually assess the fit.


Licensed by Google
* The model's **coefficient (slope)** was interpreted to understand the quantitative relationship between area and price.
## Key Results
The simple linear regression model using only area was able to explain a significant portion of the variance in house prices.

The model's coefficient indicated that for each additional square unit of area, the house price is predicted to increase by a specific amount, providing a clear and actionable insight.

## Future Work: Multiple Linear Regression
To improve predictive accuracy, this project can be extended to a multiple linear regression model by including more features like bedrooms, bathrooms, and stories in the analysis. The workflow would remain the same, but the model would learn from a richer set of input data.

## Tools & Libraries
Python

Pandas: For data loading and manipulation.

Scikit-learn: For implementing the linear regression model and evaluation metrics.

Matplotlib: For plotting the results.
