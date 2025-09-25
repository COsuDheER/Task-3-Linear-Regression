# Task-3-Linear-Regression
Key Steps and Learnings

Data Preparation: I started by importing the dataset using Pandas, which allowed me to inspect and clean the data. This is a crucial first step in any data science project.

Simple Linear Regression: I began with a basic model using only a single feature, the house's area, to predict its price.

Model Training: I used Scikit-learn's LinearRegression model to train our data.

Evaluation: I evaluated the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R^2 score. I learned that a low R^2 score (0.27) indicated that a single feature wasn't enough to accurately predict the price.

Multiple Linear Regression: To improve the model, I expanded it to include multiple features: area, bedrooms, and bathrooms.

Improved Performance: By adding more features, the model's predictive power significantly increased, as shown by the much higher R^2
score (0.46). This demonstrated the importance of feature selection in building a robust model.

Coefficient Interpretation: I learned to interpret the coefficients for each feature, which told how much the price was expected to change for a one-unit increase in that specific feature, holding all others constant.

Visualization: I used Matplotlib to create a scatter plot with a regression line, visually representing the relationship between our variables and the model's fit. I also understood why a simple 2D plot isn't possible for a multiple linear regression model due to the number of dimensions.

This project provided a solid foundation in using a complete machine learning pipeline, from data preparation and model training to evaluation and interpretation.
