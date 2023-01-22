# Weather-Classification
The aim of our project is to study and analyse the given datatset about weather conditions and classify it into categories- rain or snow. The datatset has been acquired through kaggle. Our analysis is divided into following steps: 
Knowing the Dataset
Variance Threshold
Visualization
Outlier handling
Model Implementation
Evaluation
It also involves handling of missing values, checking the shape of our dataset, figuring out the datatypes of each feature and also encoding categorical feature to numerical.
On visualizing the data using heatmap we try to analyze the correlation among various features. features with low correaltion wil be dropped. Also we check the varriablity using Various Threshold- True indicating high variabilty while false meaning less variablity. we drop the features with low variability to avoid redundancy.
The outliers are detected using IQR and were removed using flouring and capping. Log transformation is also used to check for skweness.
For model implemtation we have used Random forest algorithm and logistic regression algorithm. To evalute their results confusion matrix and classification report were implemnted.
We observed that while implenting our random forest algorithm it had overfitting of 0.17 while in logistic regression it was 0.23. Also, bothy ,models had accuracy of 98%.
