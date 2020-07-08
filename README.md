# Credit card approval Prediction

#### **Data Source**
The data [Credit Card approval dataset](http://archive.ics.uci.edu/ml/datasets/credit+approval) was extracted from the UCI machine learning repository. 

### **Data Description**
This dataset concerns credit card applications of 667 customers. There are 15 Independent variables and one dependent variable which shows if the customer will be approved a credit card or not. 

#### **Project Goal**
The goal of this project is to understand this dataset, get some insight regarding the dataset, and finally train a model that can predict ApprovalStatus for new customers

#### **Conclusion**

Four base machine learning model (Logistic regression, Support Vector Classifier, K-Nearest neighbors, Decision trees). We also used 2 ensemble learning model (Voting Classifier and Random Forest). 

We achieved the best prediction performance uisng Logistic Regression trained on the unscaled data. The confusion matrix from the unscaled data gave the least number of false positive and false negative. However, KNN neighbor model on scaled data resulted in similar accuracy score on both the training and test data. 

From exploring the data and Random Forest Classifier evaluation, the attribute that greatly determines if a customer is approved a credit card or not is PriorDefault. So, if a customer defaulted on a past credit card, they are less likely to be approved a new one.
