# Credit-Card-Fraud-Detection


## Project Intro/Objective
The purpose of this project is to predict whether the transaction is normal or fraud. 

### Methods Used
* Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling

### Technologies
* Python
* Pandas,Numpy, Scikit-learn, jupyter
 

## Project Description
This is a binary classificaiton problem, where the dataset consists of imablanced target class. So there are 2 notebooks uploaded to repo where one of the notbooks includes predicitve model results with imbalanced dataset and other with balanced dataset(using ADASYN). The aim is to correctly classify the transactions respectively. 

## Models used

- Random Forest Classifier
- Logistic Regression

## Metrics used for evaluation of models
Here we cannot completely depend on accuracy alone because its imbalanced dataset. Other metrics used are as follows

- Accuracy
- Confusion Matrix
- Precision Score
- Recall Score 
- F-beta Score

## Metric Importance
- In this case importance is given to the precision score (reducing FP i.e. reducing the number of Normal transactions classified as Fraud). It depends on the use case, whether to give importance to precision or recall and if we want to consider both then we can use the f-beta score with b = 1. With b = 0.5 importance will be given to precision considering both recall and precision and with b = 2 importance is given to recall considering both precision and recall. 

- Discussing the results with the domain expert is important as he will decide or direct on to which metric is more important.

If results from both the files are compared we can see in the imbalanced notebook the model is somewhat biased to predicting the majority of the class i.e. normal. In the next file we cna see that the results of the best model are impressive where ADASYN is used to deal with the Imbalanced class.
To study more about ADASYN [click here](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.ADASYN.html)
 
