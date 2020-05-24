# Heart-Disease-Prediction-using-Naive-Bayes
Implemented Naive Bayes Classifier in order to detect the presence of heart disease using the records of previous patients.

Dataset: Heart Disease Data Set, available from: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

heartdisease.txt has 14 different features for each patient which are as follows:
• age (in years), 
• sex (male or female), 
• cp (chest pain type), 
• trestbps (resting blood pressure in mm Hg on admission to the hospital), 
• chol (serum cholesterol in mg/dl), 
• restecg (resting electrocardiographic results), 
• thalach (maximum heart rate achived), 
• exang (exercise induced angina), 
• oldpeak (ST depression induced by exercise relative to rest), 
• slope (the slope of the peak exercise ST segment), 
• ca (number of major vessels (0-3) colored by flourosopy), 
• thal ( normal, fixed defect, reversable defect), 
• num (the predicted attribute).

A Naive Bayes Classifier was implemented from scratch without the use of any standard library and evaluated on the dataset available from UCI. 
This model was compared with the Gaussian Naive Bayes Classifier of sklearn library. 
I have used 5 random partitions of training and testing data to evaluate the implementation.


The classifier takes random partitions for 5 iterations, results were predicted with average accuracy being in the range 50% to 70%.
