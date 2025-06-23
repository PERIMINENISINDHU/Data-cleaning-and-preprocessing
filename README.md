# Data-cleaning-and-preprocessing
Medical appointment no shows dataset has been used in this task for data cleaning and pre-processing.
Load the dataset by using csv format.
For Describing first row we have been used head().
Basic Descriptive statistics syntax is used to describe the dataset.
Check for Duplicate row and remove the duplicate values bt using df.duplicated().
Check for no. of missing values and handle them by using df.isnull().sum().
To Remove missing values:df.dropna(subset=["columnname"],implace=True).
After cleaning data we have to store data in the dataset by using df.to_csv("medicaldata.csv",index=False).
