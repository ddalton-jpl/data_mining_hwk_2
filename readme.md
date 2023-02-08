# Homework 2

## How to run
- Please make sure to import the proper libraries using pip
- Run in Jupyter Notebook or VSCode

## Handling Missing Data and Interaction Data
- To handle missing data, I used the `na_values` parameter in the `read_csv` method from the `pandas` library. I set this parameter to `'?'` to indicate that any missing values in the data set should be interpreted as `NaN` values.
- I then did Label Encoding and filled in the missing values with the mean values 

- In this case the Interaction data was ignored

## Building the Classifier
- I implemented the KNN algorithm using Euclidean distance as the distance measure. 
- I first preprocessed the data. This involved encoding any categorical features and scaling the features to a common range, to ensure that features with larger values don't dominate the distance metric used by the classifier.

## Accuracy of the solution
- Accuracy: 97.81357882623706%
