# The Mobile Price Prediction
by [**dhruv-atreya**](https://github.com/dhruv-atreya)

A descriptive and predictive statistical analysis of Mobile Price dataset.

Starting with analysing of data, EDA and finally testing some Machine Learning Algorithms on this data namely,:
1. Decision Tree Algorithm
2. Gausian Naive Bayes Algorithm
3. k-Nearest Neighbour ALgorithm

The main jupyter notebook file is [Mobile_Price_Prediction.ipynb](https://github.com/dhruv-atreya/Mobile-Price-Prediction/blob/main/Mobile_Price_Prediction.ipynb). And the models creatd in this project is saved in [models](https://github.com/dhruv-atreya/Mobile-Price-Prediction/tree/main/models) folder.

#### Usage:
The model can be used using `joblib` library, using syntax,

``
model = joblib.load('<model name>.pkl')
``

``
model.predict(X)
``
