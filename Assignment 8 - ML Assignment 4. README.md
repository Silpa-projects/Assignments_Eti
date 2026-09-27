ML Assignment 4 - Regression and Evaluation Metrics
Objective

The objective of this assignment is to evaluate different regression techniques in supervised learning using the California Housing dataset.

In this assignment, different regression algorithms are implemented and their performance is evaluated using MSE, MAE, and R² score. Cross-validation and hyperparameter tuning are also performed to select the best regression model.

Dataset

The California Housing dataset is used for this assignment. The dataset is available in the Scikit-learn library and is loaded using the fetch_california_housing() function.

The dataset contains information about houses in California and their respective median house values.

The target variable is:

MedHouseVal — Median House Value

The main features are:

MedInc
HouseAge
AveRooms
AveBedrms
Population
AveOccup
Latitude
Longitude
Data Preprocessing

The following preprocessing steps are performed:

The California Housing dataset is loaded using Scikit-learn.
The dataset is converted into a Pandas DataFrame.
The dataset is checked for missing values.
Duplicate values are checked.
The features and target variable are separated.
The data is divided into training and testing sets.
Feature scaling is performed using StandardScaler.
Exploratory Data Analysis is performed to understand the features, distributions, and correlations.
Regression Algorithms

The following five regression algorithms are implemented:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
Support Vector Regressor (SVR)
Evaluation Metrics

The models are evaluated using the following metrics:

Mean Squared Error (MSE)

MSE measures the average squared difference between the actual and predicted values.

A lower MSE indicates better model performance.

Mean Absolute Error (MAE)

MAE measures the average absolute difference between the actual and predicted values.

A lower MAE indicates better model performance.

R-squared Score (R²)

R² measures how well the model explains the variation in the target variable.

A higher R² score indicates better model performance.

Cross-Validation

5-fold cross-validation is performed for all the regression models.

Cross-validation helps to obtain a more reliable estimate of model performance by dividing the dataset into different training and validation sets.

Hyperparameter Tuning

Hyperparameter tuning is performed using GridSearchCV.

Different hyperparameters are tested for the regression models to improve their performance.

The tuned models are evaluated again using MSE, MAE, and R² score.

Model Selection

The regression models are compared based on:

MSE
MAE
R² Score
Cross-validation results
Hyperparameter tuning results

The best regression model is selected based on the overall evaluation results.

Tools and Libraries Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
How to Run
Open the Jupyter Notebook.
Install the required Python libraries.
Run the notebook cells in order.
The California Housing dataset will be loaded using Scikit-learn.
Run all the preprocessing, EDA, model training, evaluation, cross-validation, and hyperparameter tuning sections.
Compare the results and identify the best regression model.
Conclusion

This assignment demonstrates the implementation and evaluation of different regression algorithms using the California Housing dataset.
