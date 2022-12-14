# Data-Cleaning
In data cleaning first one is Missing Values and second one is Handling with Outliers
1) Missing Values :
first we treat with the missing values first step is check for missing values and if missing values is less than 5% of data so remove them, if not replace with mean,median or mode (in time series data replace with before values or after value) using simple Imputer method.

2) Outliers :
For Outliers, first step to check for outliers first method is finding with boxplot and second one is based on IQR method
first method is simply remove them (less than 5% of data), second one is replace with upper limit or lower limit, otherwise replace with Arbitary outlier capper method if outliers are in more percentage then treat them sepratelly.
