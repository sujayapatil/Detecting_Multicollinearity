
# Multicollinearity

  Multicollinearity happens when independent variables in the regression model are highly correlated to each other. It makes it hard for interpretation of model and also creates overfitting problem. It is a common assumption that people test before selecting the variables into regression model.
  
# Why Multi-Collinearity is a problem?
  When independent variables are highly correlated, change in one variable would cause change to another and so the model results fluctuate significantly. The model results will be unstable and vary a lot given a small change in the data or model. This will create the following problems:
  
1.It would be hard for to choose the list of significant variables for the model if the model gives you different results every time.

2.Coefficient Estimates would not be stable and it would be hard for you to interpret the model.

3.The unstable nature of the model may cause overfitting.

# How to fix Multi-Collinearity issue?

1.Variable Selection:

The most straight-forward method is to remove some variables that are highly correlated to others and leave the more significant ones in the set.

2. Variable Transformation:

The second method is to transform some of the variables to make them less correlated but still maintain their feature.

3. Principal Component Analysis:

Principal Component Analysis(PCA) is commonly used to reduce the dimension of data by decomposing data into the number of independent factors
