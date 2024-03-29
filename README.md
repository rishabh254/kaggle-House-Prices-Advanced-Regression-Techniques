# kaggle-House-Prices-Advanced-Regression-Techniques
EDA, significance testing and modelling of the House Prices: Advanced Regression Techniques competition of Kaggle.

To know more about the competition please follow the link: 
https://www.kaggle.com/c/house-prices-advanced-regression-techniques

# Brief Overview of notebook:
* [Data Preprocessing](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - data cleaning, label encoding, making data suitable for analysis
* [Pairwise Correlations](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - pairwise Pearson correlation analysis on all pairs of 15 significant features.
* [Informative Plots](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - five informative plots revealing aspects of this data.
* [Handcrafted Scoring Function](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - a handcrafted scoring function to rank houses by “desirability”
* [Pairwise Distance Function](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - a house “pairwise distance function”, which measures the similarity of two properties
* [Clustering](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - cluster the houses using distance function into 5 to 20 classes and checking how well the clusters reflect neighborhood boundaries
* [Linear Regression](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - a simple linear regression model on one or more variables to predict the pricing as a function of other variables
* [External Dataset](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - Identify at least one external data set to integrate into price prediction analysis to make it better.
* [Permutation Test](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) - build single-variable regression models, and for each one do a permutation test to determine a p-value of how good the predictions of the housing prices are.
* [Final result](https://github.com/rishabh254/kaggle-House-Prices-Advanced-Regression-Techniques/blob/master/cse519_hw3_goel_rishabh_112714848.ipynb) -  build the best prediction model to solve the task

# Data:
The data could be found from the following link :
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

# Install:
To run this notebook:

1. Clone the repository.
2. Install [virtualenv](http://virtualenv.readthedocs.org/en/latest/installation.html).
3. Navigate to the directory where you unzipped or cloned the repo and create a virtual environment with `virtualenv env`.
4. Activate the environment with `source env/bin/activate`
5. Install the required dependencies with `pip install -r requirements.txt`.
6. Execute `ipython notebook` from the command line or terminal.
7. When you're done deactivate the virtual environment with `deactivate`.


# Dependencies:
* [NumPy](http://www.numpy.org/)
* [IPython](http://ipython.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Seaborn](https://seaborn.pydata.org/)
* [Matplotlib](http://matplotlib.org/)
* [LightGBM](https://lightgbm.readthedocs.io/en/latest/)
* [XGBoost](https://xgboost.readthedocs.io/en/latest/)

I have been using colab for this project. 

# Goal:
The goal for the competition is to predict sales prices and practice feature engineering, RFs, and gradient boosting.

