# Telemarketing Data analysis

Analyzing marketing campaign datasets of banks is crucial for banks to stay competitive, improve their marketing strategies, and ultimately, better serve their customers. It has numerous benefits which include Understanding Customer Behaviour, identifying new opportunities, improving telemarketing strategies, and many more.
This project is about analyzing a marketing campaign dataset of a Portuguese banking institution. It aims to develop Machine Learning that can accurately predict the likelihood that a customer will subscribe to a term deposit. The dataset in this project was taken from UCI Machine Learning Repository.

## About the Dataset

The data used had several different features that are useful for telemarketing agencies. It included:
+ Client Data: age, job, marital status, education, previous housing loan, and previous personal loan.
+ Related to the last contact of the current campaign: Last communication type, Last contact month, Day of the week contacted, and duration.
+ Miscellaneous attributes: No of contacts in this campaign, Days since the last contact, No of contacts in previous campaign, and Outcome of the previous campaign
+ Social and Economics Attributes: Employee Variation Rate, Consumer Price Index, Consumer Confidence Index, Euribor 3-month rate, and Number of Employees

## Methodology
We start the project with the Exploratory data analysis. It includes identifying outliers, getting count of null and unknown values, correlations between the features and getting insight about the symmetry and distribution of data and features. It helped us to identify major class imbalance prpoblem in the dataset. Next step is the pre processing the data which includes scaling the necessary features, handling outliers and removing unnecessary features based on the conclusion obtained from EDA. It also includes using SMOTE algorithm to address the major issue of class imbalance. Finally, machine learning classification models were applied. Models like SVM, Tree-based models, KNN, DNN etc were applied, and the best ones were taken. Since tree-based models worked the best, hence these are shown in the code file.

## Conclusions
Tree based models were found to be highly accurate and also handled the flaws in data really well. Gradient boost was found to be the best working model with certain hyperparameters that were derived using GridSearchCV and Cross Validation techniques. The final achieved an outstanding accuracy of 93.45% with F1 score of 93.31, precision of 91.41%, recall of 95.31% and AUC-ROC score of 93.52%. This indicates that model is able to precisely segregate the 'no' and 'yes' classes.

## Contributors: 
+ Rohit Jalani
+ Adhithyan Sivakumar
+ Atif Rehman
