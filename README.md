# Sales-Advertising-
Using Linear Regression Implementation with Python

# Import the libraries
import pandas as pd
import numpy as np
import seaborn as sns
from matplotlib import pyplot as plt

Read the file
check the data set imported or not 

Data understanding and exploration
let's check for missing values
Dropping an unnecessary column - Unnamed: 0

to check all the columns

To check unique values in a column

Let's detect outliers
Boxplot to detect outliers

we fix the outliers - IQR = Q3-Q1

we need to separate X(independent variables) and y dependent variable

Let's train the model
For model training - X_train,y_train - fit
Model testing - X_test - predict - y_pred
evaluate -metrics - mse, or rmse for regression, classification - accuracy_score,precision,recall,f1 - y_test,y_pred

Testing and Evaluation

calling sqroot function from numoy to apply root mean squared error

finally import the gradio