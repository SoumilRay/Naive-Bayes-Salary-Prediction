# Naive-Bayes-Salary-Prediction

https://archive.ics.uci.edu/ml/datasets/Adult
This dataset contains over 32,000 instances of individuals, with 14 features describing demographic and employment information. The target variable is whether the individual earns over $50k per year. The features are assumed to be independent, making it a good fit for Naive Bayes classification.

Implementation steps:
Loaded the dataset into a pandas DataFrame
Split the dataset into training and testing sets
Implement a function to calculate the prior probability of each class (benign and 
malignant) in the training set
Implemented a function to calculate the conditional probability of each feature given to 
each class in the training set
Implemented a function to predict the class of a given instance using the Naive Bayes 
algorithm
Implemented a function to calculate the accuracy of your Naive Bayes classifier on the 
testing set
