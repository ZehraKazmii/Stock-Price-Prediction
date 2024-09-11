# Stock Price Prediction
This project aims to predict stock prices for "The State Bank of Pakistan" using machine learning regression algorithms. The dataset, which includes historical stock data, was sourced from Yahoo Finance.
# Algorithms
Linear Regression
SVR
Random Forest
Gradient Boosting Models (GBM)
Extreme Gradient Boosting (XGBoost)
AdaBoostRegressor
Decision Tree
KNeighborsRegressor(KNN)
Artificial Neural Networks (ANN)
LSTM(Long Short term Memory)
# Structure
data/: Contains the dataset files.
notebooks/: Jupyter notebooks with the code for data exploration, preprocessing, and model training.
src/: Python source code for the project.
requirements.txt: List of dependencies needed to run the project.

# Run
Install dependencies using pip install -r requirements.txt.
Execute the notebooks in the notebooks/ folder in the given order.
Run the scripts in the src/ folder for further analysis or model training.
# Conclusion
We can clearly see in the accuracy chart that the accuracy of the algorithms - "2", "6", "8" and "10" are the highest.
But when we see the rmse chart we find that the algorithms "2" and "8" is unusually high.
So we conclude that the algorithms "6" and "10" i.e. AdaBoostRegressor and LSTM(Long Short term Memory) have performed very well both in terms of accuracy and rmse.
