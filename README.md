# retail_sales_prediction_Susanta-_adhikary

This dataset is a live dataset of Roseman Stores. On analsysing this problem we observe that Roseman problem is a regression problem and our primarily goal is to predict the sales figures of Roseman problem. In this Notebook we work on following topics

Analysing the Dataset by using Exploratory Data Analysis. Using Exponential Moving Averages analyse Trends and Seasonality in Roseman dataset. Analyse Regression analysis using following prediction analysis,

A. Linear Regression Analysis.

B. Elastic Regression ( Lasso and Ridge Regression).

C. Random Forest Regression.

D.adaboost and Xgboost).

By applying above algorthim we find accuracy.

After analysis we saw that Sales column contains 172817 rows with 0 sale. So we created a new dataframe in which we removed 0 sales rows and tried to train our model. We used various algorithms and got accuracy score around 74%.

We were also curious about the total dataset(including Sales = 0 rows). So we trained another model using various algorithms and we got accuracy near about 98% which is far better than previous model.

So we came to conclusion that removing sales=0 rows actually removes lot of information from dataset as it has 172817 rows which is quite large and therefore we decided not to remove those values.We got our best rmpse score from Random Forest model,Graident boosting technique like adaboost ,Xgboost,we tried taking an optimum parameter so that our model doesnt overfit.
