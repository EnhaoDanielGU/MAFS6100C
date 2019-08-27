This folder saves the past results for Linear Regression, calculated by the module linear_regression.py in the root.

For the spydata files, they can be imported by spyder in the "Variable explorer" window. This window is next to the IPython Console window.


Among them, it's worthy to take a look at
taiwan_0050_linreg_continu.spydata 

This data file is calculated by training linear regression models (with intercept, features not normalized) on the past 180 trading days, to predict the very next trading day. 
It includes the in-sample and out-of sample R2, winning ratio, their corresponding coefficients, absolute t-values, p-values, for 5 labels and different starting day. There are 233 - 180 - 1 = 52 starting days in total. 
All the results are recorded in format of dictionaries.
