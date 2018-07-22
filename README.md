# Backward-Elimination

This python file provides the functionality to optimise the dataset for Multiple Regression Models using Backward Elimination.
Columns are first dropped using the adjusted R-Squared values and then to further optimise the data, p-values of the columns are also checked.

Pass the features(X) followed by the labels(y) and the significance level you want to consider into the backward_eliminaton function. It will return the optimised dataset.

Import the following libraries for the code to work properly.

import pandas as pd

import statsmodels.api as sm

import numpy as np

For any suggestions/mistakes ping me at: anishgoyal2406@gmail.com
