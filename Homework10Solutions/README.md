# MANE 6399 - Data Science

## Homework 10 - More Classification Techniques

### Assigned: April 23, 2020
### Due: May 1, 2020 (no late submissions)

Use the Vertebral Column Data Set from the UCI Machine Learning Repository that was used for Homework  Assignments 8&9. This data set contains 6 attributes that are used to determine the state of a person's spine. Each person's spine is labelled as DH, SL, NO or AB.

The column names for the data set (taken from the UCI Machine Learning Repository) are provided below.

![Column Names](E:/DataScienceSpring2020/Homework/Homework8/homework8Labels.png "Column Names")

#### Problem 1

Fit a MLPClassifier model to the vertebral data set. Explain your choice of the network configuration.
Report the accuracy and confusion matrices for the training and testing set. How well does this technique work?

#### Problem 2

Apply the GridSearchCV to finding the best set of parameters for the SVMClassifier by examining the parameters of kernel, C and gamma.


#### Problem 3

Fit an SVMClassifier model using the parameters found in Problem 2. Report the accuracy and confusion matrices for the fitted model.

#### Problem 4

Review the DecisionTreeClassifier. Utilize the GridSearchCV to find the optimal values of max_depth,
min_samples_split, and min_samples_leaf. Fit the DecisionTreeClassifier using the parameters found in GridSearchCV and report the accuracy and confusion matrics for the training and test sets.