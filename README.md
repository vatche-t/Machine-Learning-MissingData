# Machine-Learning-MissingData
How to solve Missing data by using different strategies


using imputer functions by calling the sklearn library.
the given parameters for Simpleimputer are:

missing_valuesnumber, string, np.nan (default) or None
The placeholder for the missing values. All occurrences of missing_values will be imputed.

strategystring, optional (default="mean")
The imputation strategy.

If "mean", then replace missing values using the mean along each column. Can only be used with numeric data.

