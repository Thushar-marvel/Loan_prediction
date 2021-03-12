# Predict Loan Eligibility for Dream Housing Finance company

# Problem statement
Dream Housing Finance company deals in all kinds of home loans. 
They have presence across all urban, semi urban and rural areas. Customer first applies for home loan and after that company validates the customer eligibility for loan.
Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. 
These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. 
To automate this process, they have provided a dataset to identify the customers segments that are eligible for loan amount so that they can specifically target these customers. 



# Dataset
Dataset set is downloaded from analytics vidya hackathon.The data set consist of 

# libraries
The packages are Pandas to load data and to do data analysis, Numpy to work with arrays, scikit-learn is used for building the model and evaluating it,
seaborn and matplotlib for data visualisation, pydotplus to visualize the decision tree and finally xgboost model

# Data analysis
Exploring the dataset to gain an understanding of the type, quantity, and distribution of data in our dataset. 
Data analysis is done to check any outliers ,missing values and categorical variables in the dataset. Data visualization is done using seaborn and matplotlib pacakges
Outliers are treated using capping and flooring technique

# Creating training and testing data 
Using scikit-learn train-test split function data set is divided 80% as train and 20% as test.

# Creating model 
Using scikit-learn 9 different classification models are built.
Logistic regression,LDA,Decision tree, random forest, bagging,Ada boost,gradient boost, xgboost,KNN , SVM classifiers.

# Model evaluation
We evaluated our built models using the evaluation metrics provided by the scikit-learn package. 
The evaluation metrics we are going to use are the accuracy score metric, recall,roc_curve, and finally the confusion matrix.



![image](https://user-images.githubusercontent.com/69953585/110892354-ea1b2280-8319-11eb-883f-0a084af117de.png)

