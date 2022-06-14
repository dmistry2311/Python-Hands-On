# Python-Hands-On

Data imputation with the nearest matching row within the excel.

This code is NOT using any in-built libraries to impute the data, instead, I found the distance between rows using the function of the Euclidean distance (from sklearn) and replacing the NaN value with the nearest non-NaN value based on the distance calculated by the Euclidean distance function.
