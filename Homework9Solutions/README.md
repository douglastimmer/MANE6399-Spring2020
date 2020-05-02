# MANE 6399 - Data Science

## Homework 9 - Decision Trees

### Assigned: April 16, 2020
### Due: April 24, 2020

Use the Vertebral Column Data Set from the UCI Machine Learning Repository that was used for Homework 8 Assignment. This data set contains 6 attributes that are used to determine the state of a person's spine. Each person's spine is labelled as DH, SL, NO or AB.

The column names for the data set (taken from the UCI Machine Learning Repository) are provided below.

![Column Names](E:/DataScienceSpring2020/Homework/Homework8/homework8Labels.png "Column Names")

#### Problem 1

Fit a decision tree (DecisionTreeClassifier) with default parameters (all blank) to the Vertebral data set. Report the accuracy of the decision tree for both the training and testing data sets. Also generate a confusion matrix and use graphviz to generate a graphical decision tree.

#### Problem 2

Select a parameter for the decision tree created in Problem 1 and change its value and refit the model. Explain the reason for selecting your parameter and the impact that you expect to observe upon the structure and performance of the decision tree. Once again, calculate accuracy scores for both the training and test sets, generate a confusion matrix and use graphviz to generate a graphical decision tree. Did the change in parameters meet your expectations? (please explain)

#### Problem 3

Use the extreme gradient boost classifier (GradientBoostClassifier) to fit a model  with default parameters (all blank) to the Vertebral data set. Report the accuracy of the decision tree for both the training and testing data sets as well as generate a confusion matrix.

#### Problem 4

Select a parameter for the extreme gradient boost classifier model created in Problem 3 and change its value and refit the model. Ideally, you will select a different parameter than the one used in Problems 2. Explain the reason for selecting your parameter and the impact that you expect to observe upon the structure and performance of the model. Once again, calculate accuracy scores for both the training and test sets, and generate a confusion matrix. Did the change in parameters meet your expectations? (please explain)

#### Problem 5

Use the random forest classifier (RandomForestClassifier) to fit a model  with default parameters (all blank) to the Vertebral data set. Report the accuracy of the decision tree for both the training and testing data sets as well as generate a confusion matrix.

#### Problem 6

Select a parameter for the random forest classifier model created in Problem 5 and change its value and refit the model. Ideally, you will select a different parameter than the ones used in Problems 2 and 4. Explain the reason for selecting your parameter and the impact that you expect to observe upon the structure and performance of the model. Once again, calculate accuracy scores for both the training and test sets, and generate a confusion matrix. Did the change in parameters meet your expectations? (please explain)
