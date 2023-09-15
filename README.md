# Weather-Classification
# Objective: 
The aim of our project is to study and analyze the given dataset about weather conditions and classify it into categories- rain or snow. The dataset has been acquired through Kaggle.
Our analysis is divided into the following steps: 
Knowing the Dataset
Variance Threshold
Visualization
Outlier handling
Model Implementation
Evaluation
# EDA: 
It involves handling missing values, checking the shape of our dataset, figuring out the datatypes of each feature and encoding categorical features to numerical using a label encoder. On visualizing the data using a heatmap we try to analyze the correlation among various features. features with low correlation will be dropped. Also, we check the variability using Various Threshold- True indicates high variability while false means less variability. we drop the features with low variability to avoid redundancy.
# Outliers: 
The outliers were detected using IQR and were removed using flouring and capping. Log transformation is also used to check for skewness. if the skewness of the feature is less than that of a feature when it is log-transformed then we use the original feature else we use the transformed one.
# Model: 
For model implementation, we have used the Random forest algorithm and logistic regression algorithm. The random forest avoids overfitting by picking random groups of data and logistic regression as it is commonly used for binary classification. To evaluate their results confusion matrix and classification report were implemented.
# Observations
We observed that while implementing our random forest algorithm it had an overfitting of 0.17 while in logistic regression it was 0.23. Also, both, models had an accuracy of 98%. This indicates that our model highly overfits meaning it has high variance and another reason could lack of optimum features.
