## A salary predictor regression model for an unknown company

After features were formatted and added thanks to 
my talented classmate Elena, several different regressor models were run on the data,
The highest performing model was the Extra-Trees Regressor, with 
a 70% Variance score on the test set.

However in an attempt to adjust the model to account for 
certain outliers the RANSACregressor was wrapped around the models.
This produced a very different result; The wrapper broke the Extra-trees regressor 
and the simple Linear Regression and Support Vector Machine 
using the linear Kernel reported about an 80% Variance score on the test set. 


