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

we selected 8 best features for model creation.
