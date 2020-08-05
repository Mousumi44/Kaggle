# Fun in Kaggle!!!
Real or Not? NLP with Disaster Tweets
--------------------------------------
This is part of the [Competition](https://www.kaggle.com/c/nlp-getting-started) where you’re challenged to build a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t.

My Contribution:
* Exploratory Data Analysis
* Preprocessing 
* Wordcloud for common words in real and non-real tweets
* Build a DNN model with Bidirectional GRU with public score of 0.71437

House Prices: Advanced Regression Techniques
---------------------------------------------
This is part of the [Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques) where you’re challenged to predict the final price of each home WITH With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa.

My Contribution in [Notebook-EDA](https://github.com/Mousumi44/Kaggle/blob/master/House_Prices.ipynb):[Ref](https://www.kaggle.com/pmarcelino/comprehensive-data-exploration-with-python)
* Relationship of 'SalePrice' with numerical and categorical variable
* Heatmap and scatterplot of 'SalePrice' and correlated varaibles
* Outlier identification with Bivariate analysis
* Check for 'normality', 'skewness' and 'homoscedasticity' 
* Log Transform data to attain normality
* Convert categorical variable into dummy

My Contribution in [NOtebook-MOdeling](https://github.com/Mousumi44/Kaggle/blob/master/HousePrice_Modeling.ipynb)
* Data Preprocessing
  * Identify and remove outliers
  * Log Transform data to attain normality
* Feature Engineering
  * Identify and impute missing data
  * Transforming some numerical variables that are really categorical
  * Label Encoding some categorical variables that may contain information in their ordering set
  * Box Cox Transformation of (highly) skewed features
 * Modeling
  * LASSO, Elastic Net, Kernel Ridge, Gradient Boosting, XGBoost, LightGBM
  * Stacking models
    * Averaging base models
    * Add a meta-model on averaged base models and use the out-of-folds predictions of these base models to train meta-model
    * Ensembling StackedRegressor, XGBoost and LightGBM
The submission is in Top 6% 
  
  
