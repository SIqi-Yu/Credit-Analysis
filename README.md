# Credit Risk Analysis
By Lucy Yu and Ruolin Zhao 
from Team 28


# This is a introduction to our project
## dataset:

 - Over the years, the company has collected basic bank details and gathered a lot of credit-related information. The management wants to build an intelligent system to segregate the people into credit score brackets to reduce the manual efforts.
 - This is a link to origin dataset[Credit Score Classification Clean Data](https://www.kaggle.com/datasets/clkmuhammed/creditscoreclassification)

## Analysis(EDA):

 - Q1:What is the relationship between age and credit score ?
 - Q2:What is the relationship between annual income and credit score ?
 - Q3:What is the relationship between installment amount and credit score ?


## Prediction(Machine Learning):
 - Above all, finance institutions suffer a big risk when deciding to lend loans to customers or not, as we mentioned before, large proportion of people incline to borrow large amount of money. It is essential to construct a system that can provide help and make efficient decisions. We try to solve this problem by using machine learning. The get_dummies method in pandas is used to perform One-Hot coding for categorial statistics. Also SMOTE method to slove the imbalanced class problem. And we use stacking classifier to predict the ciredit score. The final accuracy rate of our model is more than 0.87, which is considerably precise.
 - Banks can predict with high accuracy whether or not one person is trustworthy with this model. Consequently, they can increase revenue and avoid potential losses.
