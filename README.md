# Loan-Repayment ML Project


Here are the project steps and what you learned from the Loan Repayment Prediction project using ensemble learning methods:

Objective:

The main goal was to predict whether a bank should approve a loan for an applicant based on their profile using ensemble learning methods.
Data Importing and Preparation:

Imported necessary libraries for data manipulation, visualization, and machine learning.
Loaded the dataset and performed initial data exploration to understand the structure and contents.
Dealt with categorical data by encoding the 'purpose' attribute using label encoding.

Data Exploration and Visualization:

Conducted exploratory data analysis (EDA) to visualize the distribution and relationships between different features.
Created histograms, count plots, and heatmaps to identify patterns and correlations within the data.

Data Preprocessing:

Checked for and confirmed there were no missing values in the dataset.
Split the dataset into training and testing sets to evaluate the model's performance.

Model Building and Evaluation:

Decision Tree Classifier:

Performed hyperparameter tuning using GridSearchCV to find the best parameters.
Evaluated the model's performance using confusion matrix, classification report, and accuracy scores.

Bagging with Decision Tree:

Implemented a bagging classifier with a decision tree as the base estimator.
Evaluated its performance using cross-validation.

AdaBoosting with Decision Tree:
Applied AdaBoosting on a decision tree to see if boosting techniques improve the model's performance.

Random Forest Classifier:
Built a random forest model and evaluated its accuracy.

AdaBoosting with Random Forest:
Combined AdaBoost with the random forest classifier and assessed its performance.

Gradient Boosting:
Used gradient boosting for further model improvement and compared its performance with other models.
Conclusion:

Learned that while using different ensemble learning techniques like bagging and boosting, the models provided similar results with minimal differences in accuracy.

Gained insights into the strengths and weaknesses of various ensemble methods and their impact on model performance.
