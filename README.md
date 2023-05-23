# CodeClause__Fraud_Detection
In this project we are trying to detect the fraud done using credit cards.
First we've downloaded the dataset from kaggle website ,now we can see we've column names v1,v2,v3.......v29 these are confidential info about the data which we cant figure out,then we've amount spend by credit card then class that is our target variable. 
class 0 means normal transaction ,class 1 means fraudelent transaction 

So the steps which we need to follow are :-
Step1: To make our dataset balanced (by undersampling and oversampling as our class has many 0 but very few 1 )
Step2: After getting balanced data we will predict the target variable using various models such as logistic regression,decision tree,random tree 
Step3: Here, after performing these models we will compare the accuracy score of the best model 
Step4: Save the model and predict whether the transaction is normal or fraud

