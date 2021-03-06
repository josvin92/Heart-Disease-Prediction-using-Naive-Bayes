# Heart-Disease-Prediction-using-Naive-Bayes
Implemented Naive Bayes Classifier in order to detect the presence of heart disease using the records of previous patients.

Dataset: Heart Disease Data Set, available at: https://archive.ics.uci.edu/ml/datasets/Heart+Disease

The dataset has 14 different features for each patient which are as follows:
* age (in years), 
* sex (male or female), 
* cp (chest pain type), 
* trestbps (resting blood pressure in mm Hg on admission to the hospital), 
* chol (serum cholesterol in mg/dl), 
* restecg (resting electrocardiographic results), 
* thalach (maximum heart rate achived), 
* exang (exercise induced angina), 
* oldpeak (ST depression induced by exercise relative to rest), 
* slope (the slope of the peak exercise ST segment), 
* ca (number of major vessels (0-3) colored by flourosopy), 
* thal ( normal, fixed defect, reversable defect), 
* num (the predicted attribute).

1. A Naive Bayes Classifier was implemented from scratch without the use of any standard library and evaluated on the dataset obtained from UCI. 
2. This model was compared against the Gaussian Naive Bayes Classifier of sklearn library. 
3. The classifier takes 5 random partitions of training and testing data to evaluate the implementation.
4. Results were predicted with accuracy being in the range 50% to 70%.
