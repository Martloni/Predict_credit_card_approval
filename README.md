# Credit card approval Prediction

This project was inspired by my credit card application process which was not granted. The analysis of this project was to provide some information that banks look for in applicants before granting a new credit card. 

#### **Data Source**
The data [Credit Card approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) was extracted from the UCI machine learning repository. 

### **Data Description**
This dataset concerns credit card applications of 667 customers. There are 15 Independent variables and one dependent variable which shows if the customer will be approved a credit card or not. 

#### **Project Goal**
The goal of this project is to understand this dataset, get some insight regarding the dataset, compare different machine learning algorithms on predicting the approval status for a new applicant. Also, based on this sample dataset, what are the most important features that allows for banks to approve credit card to new applicants

#### **Conclusion**
Following the training of differerent machine learning classifier on this dataset used together with cross validation, we achieved the maximum prediction performance (i.e accuracy) with Linear Support Vector Machine (SVM) algorithm. 

![Image 1](https://github.com/Martloni/Predict_credit_card_approval/blob/master/machine_learning_comparison.png)



Also, from the analysis of this dataset, the two most important features that determines credit card approval are Prior Default and Credit score. This makes sense since banks need to know if they can rely on applicants to pay back their credit card loan. 

![Image 2](https://github.com/Martloni/Predict_credit_card_approval/blob/master/feature_ranking.png)
