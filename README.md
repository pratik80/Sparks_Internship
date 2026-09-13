Data Science and Business Analytics
Task 1: Prediction Using Supervised Learning
Problem Statement

Predict the percentage score of a student based on the number of hours they studied.

Dataset

The dataset contains two variables:

Hours — Number of hours a student studied.
Scores — Percentage score obtained by the student.

Dataset: http://bit.ly/w-data

Objective

The objective of this task is to build a Supervised Machine Learning model that can predict a student's score based on their study hours.

Machine Learning Algorithm

For this task, Simple Linear Regression is used because there is one independent variable (Hours) and one dependent variable (Scores).

The linear regression equation is:

y = mx + c


Where:

y = predicted score
x = number of study hours
m = slope of the regression line
c = intercept
Technologies Used
Python
Jupyter Notebook / Google Colab
Pandas
NumPy
Matplotlib
Scikit-learn
Project Workflow
Import the required libraries.
Load the dataset.
Explore and visualize the data.
Split the dataset into training and testing sets.
Train a Linear Regression model using the training data.
Make predictions using the test data.
Compare the predicted values with the actual values.
Evaluate the model using an appropriate performance metric.
Predict the score for a given number of study hours.
Sample Prediction

One of the commonly asked predictions in this task is:

What will be the predicted score if a student studies for 9.25 hours/day?

The trained Linear Regression model can be used to obtain the predicted score.

Model Evaluation

The model can be evaluated using metrics such as:

Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
R² Score

These metrics help determine how accurately the model predicts student scores.

Results

The Linear Regression model establishes a relationship between study hours and student scores. The results can be visualized using a scatter plot along with the fitted regression line.

Conclusion

This project demonstrates how Supervised Learning can be used to predict a student's academic score from their study hours. Simple Linear Regression provides an effective approach for modeling the relationship between these two variable

