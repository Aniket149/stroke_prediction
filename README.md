# Code and Resource used
* Python version: 3.8.3
* Packages: Pandas, Numpy, Matplotlib, Seaborn, scikit learn
* Data Collection: Kaggle Dataset- https://www.kaggle.com/fedesoriano/stroke-prediction-dataset

# Feature Engineering

* In Dataset, Only BMI feature containg missing value. We imputed missing value with Mean.
* Stroke feature consist of 0 value count more than 1 value count. We have imbalance dataset. the count of 0 and 1 should be same. stroke feature is our target variable. we use sample method for balancing dataset. The sampling technique we have used are called as 'Over Sampling'. The benefit of over sampling is we dont loose any data.
* The categorical features, gender, ever_married, work_type, residence_type are converted into numerical form for applying machine learning algorithm.

# Feature Selection

we used three feature selection technique to find out best features for model creation.
* chi square
* feature importance
* correlation technique

we selected 8 best features for model creation. The following features are selected for model creation
* age
* avg_glucose_level
* hypertension
* heart_disease
* work_type
* ever_married
* bmi
* smoking_status

# Model Creation

This is classificaication problem. we have to predict patients are having stroke or not. we used classification algorithms. The random forest algorithm gives better accuracy. so we create model using random forest.
Model Accuracy - 99.97%

# Model Deployment

We create application using Flask and deploy it on heroku.
application link - https://stroke-api.herokuapp.com/


