# Heart-Disease-Prediction
This project mainly focuses on heart disease prediction in patients using a support vector machine (SVM) 
classifier. We have so many different datasets particularly, but mainly focused on the dataset is the 
processed.cleveland.data dataset from the UCI Machine Learning repository file. We preprocessed the 
data by handling missing values and converting the target values to binary. Then we need to split it into 
training sets, testing sets and standardize the features. We trained an SVM classifier with a linear kernel 
and C=1 on the training set, made predictions on the testing dataset and calculate the model performance 
using precision, accuracy, F1-score, recall and confusion matrix. 
We also visualized the data using a correlation matrix, histograms, box plots, and a pair plot. We 
performed hyperparameter tuning using GridSearchCV with a StratifiedKFold cross-validation and 
trained the SVM classifier with the best parameters. We then made predictions on the testing set again 
and evaluated the model's performance with the same metrics as before. 
Our SVM classifier achieved an accuracy of 93.33% and outperformed the baseline model, which always 
predicts no heart disease. The correlation matrix and visualizations helped us gain insights into the 
relationships between features and the target variable. 
Overall, this project demonstrates the potential of SVM classifiers for heart disease prediction, but further 
research is needed to address the limitations of the approach, such as the reliance on standardized data and 
assumptions of linear separability. 

# Input dataset: 
https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/ 
The processed.cleveland.data dataset from the UCI Machine Learning Repository, which contains 303 
instances and 14 features related to heart disease medication. 
