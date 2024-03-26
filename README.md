# Used-Car-Price-Prediction
The primary objective of this project is to develop a robust framework that can accurately predict the price of a given used car based on its various features.
It is a regression problem not a classification problem, as the goal is to predict a continuous value
(the price in this case) rather than class labels.Therefore, there are no distinct classes here.
We used various Machine Learning algorithms and selected the best model for our datasets.
2 Methods
The first step involved the preprocessing of data and data cleaning. We first loaded the training
and training data targets and combined them.Then we performed mean inputing for dealing with the
missing values. Then we dropped the rows with null values and checked for outliers. After that, we
removed outliers for various features. Then to make the target variable linear with respect to features,
we took the log of instances (log Price). The second step involved Encoding of categorical columns.
For Brand and Location columns, we used Target Encoding and for Fuel Type, Transmission, and
Owner Type, we used One Hot Encoding. In the third step, we performed various machine learning
algorithms with hyperparameter tuning using Grid SearchCV.
3 Experimental Setup
We used 8 Regression algorithms with Hyperparameter tuning with GridSearchCV
1. Linear Regression
2. Decision Tree Regression
3. Random Forest Regression
4. Ridge Regression
5. Support Vector Regression
6. K Nearest Neighbour Regression
7. Gradient Boosting Regression
We used these seven algorithms.
First, we had to perform encoding techniques. We performed target encoding on Brand and Location
columns as there were many unique categorical values. On Fuel, Transmission, and Owner columns,
we performed One Hot Encoding.
Then we performed Hyperparameter tuning and implemented our algorithms and recorded the
performance.

