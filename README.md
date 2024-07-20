# FakeNewsPrediction

Steps
1. Collection of data
  https://www.kaggle.com/c/fake-news/data?select=train.csv
2. Data pre-processing
3. Splitting data into test-train data.
4. Training the model with above data.
5. Evaluating the model first on train data itself then on test data
   
# Logistic Regression
Logistic regression is used for binary classification where we use sigmoid function, that takes input as independent variables and produces a probability value between 0 and 1.
For example, we have two classes Class 0 and Class 1 if the value of the logistic function for an input is greater than 0.5 (threshold value) then it belongs to Class 1 otherwise it belongs to Class 0. It’s referred to as regression because it is the extension of linear regression but is mainly used for classification problems.


 ![image](https://github.com/user-attachments/assets/29c70306-85b0-4593-b79b-f068898fffb4)


-Logistic regression predicts the output of a categorical dependent variable. Therefore, the outcome must be a categorical or discrete value.
-It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.
-In Logistic regression, instead of fitting a regression line, we fit an “S” shaped logistic function, which predicts two maximum values (0 or 1).
