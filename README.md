# Phishing-Detector-with-LR-
![image](https://user-images.githubusercontent.com/104493750/180500421-65540d32-d36f-4959-8346-3c540054a6c0.png)
DESCRIPTION

Background of Problem Statement :

You are expected to write the code for a binary classification model (phishing website or not) using Python Scikit-Learn that trains on the data and calculates the accuracy score on the test data. You have to use one or more of the classification algorithms to train a model on the phishing website dataset.

Problem Objective :

The dataset is a text file which provides the following resources that can be used as inputs for model building :

 A collection of website URLs for 11000+ websites. Each sample has 30 website parameters and a class label identifying it as a phishing website or not (1 or -1).
The code template containing these code blocks:
Import modules (Part 1)
Load data function + input/output field descriptions
The dataset also serves as an input for project scoping and tries to specify the functional and non-functional requirements for it.

Domain: Cyber Security and Web Mining

Questions to be answered with analysis :

Write the code for a binary classification model (phishing website or not) using Python Scikit-Learn that trains on the data and calculates the accuracy score on the test data.
Use one or more of the classification algorithms to train a model on the phishing website dataset.
Analysis Tasks to be performed:

Initiation :
Begin by creating a new ipynb file and load the dataset in it.
      + Exercise 1 :
Build a phishing website classifier using Logistic Regression with “C” parameter = 100. 
Use 70% of data as training data and the remaining 30% as test data.                                                                                        
[Hint: Use Scikit-Learn library LogisticRegression ]                                                                                                                                                                                                   
[ Hint: Refer to the logistic regression tutorial taught earlier in the course ]
Print count of misclassified samples in the test data prediction as well as the accuracy score of the model. 
 

      + Exercise 2 :
Train with only two input parameters - parameter Prefix_Suffix and 13 URL_of_Anchor.
Check accuracy using the test data and compare the accuracy with the previous value.
Plot the test samples along with the decision boundary when trained with index 5 and index 13 parameters.
