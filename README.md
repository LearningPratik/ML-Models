# Data Science Portfolio
Repository containing portfolio of data science projects completed by me

# Motivation
I First learned these algorithms and to understand them better, used some datasets from kaggle to apply the algorithms.

## Contents

- ### Machine Learning - These are some Mini ML projects, applied a lot a things and learned a lot of things

	- [Car Price Prediction](https://github.com/LearningPratik/ML-Models/tree/main/CarPrice): A model to predict the Car's Selling price, where I used Linear Regression to predict the continuous values, also did EDA before splitting to understand the relationship between the independent and dependent variables, as there were several features to select from for the model training, also used metrics like - MAE, MSE and R-squared to understand model's performance.
  - [Salary prediction](https://github.com/LearningPratik/ML-Models/tree/main/Salary): A model to predict salary based on some features, did EDA and learned about Outliers  (how to identify them and deal with them) and learned about some of statistical topics such as - Mean, median, mode , standard deviation and quartiles also how to deal with Missing values, used Linear Regression - as it was a small dataset and also used metrics.
  - [Loan Prediction](https://github.com/LearningPratik/ML-Models/tree/main/LoanPred) : This model was for a classification dataset, where prediction were for Loan approved or not approved, here I learned about various handling methods for Missing values such as - SimpleImputer, KNN Imputer based on the relationship of that particular variable. Also did EDA to understand relationship of variables, handles categorical features using methods like LabelEncoding and Map function to manually encode the values. Checked the skewness of the data and which Scaler to use depending on the skewness of the data. Also learned about the distribution of the data. For the metrics of a classification model, I used confusion matrix to understand the TPR and FPR and is my model able to distinguishes between two labels(Using AUC score, Precison, recall and f1-score ) and to further improve model I used various algorithms such as SVC and Decision Tree, Used GridSearchCV to get the best estimators for the dataset
  

	Libraries : scikit-learn, Pandas, Seaborn, Matplotlib, Numpy.


#### Explanation to various topics which I used and learned are given in the notebook itself, refer those and correct it if required
