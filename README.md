# Competi_ML

Diamond pricing competition.

I am building this notebook for the purpuse of creating a ML model that could predict the price of diamonds based on its carat, cut, color, clarity and dimensions.
In order to do so, the project goes through the analysis of 40,000 diamonds with their specific characteristics and prices.


What it is being used:

- Linear regression
- Random Forest
- Decision tree Regressor
- KNeighbors Regressor
- XGB Regressor
- LGBM regressor

Results:

- The most deterministic characteristic for pricing is the charat
- The bigger the size the bigger the carat



The best predicting model appears to be XGB Regressor with a RMSE of a 532 aprox. (calculated using cross validation)

Tech:
- Python 3.8.5
- Pandas 1.1.3
- Seaborn 0.11.0
- Numpy 1.19.2
- Scipy 1.5.4
