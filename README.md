# Predicting House Prices 

### Data set
https://archive.ics.uci.edu/ml/machine-learning-databases/housing/

### Environment
- Anaconda
- Jupyter Notebook
- Python 3

## Liraries
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- statsmodules

## Exploratory Data Analysis (EDA)
- Data formatting, labeling
- Count, mean, min, max, std
- Pair Plots
- Correlation Analysis

## Models

### Linear Regression
### Robust Regression
### Multiple Regression
- StatsModule
- Feature Extraction (Identify important and not important)
	- Correlation Matrix Analysis
	- Collinearity with Eigenvectors
        - Standardize Variable
	- R^2 to identify key features

### Gradient Descent
- Minimize cost function
- MSE Cost Function
- Cost Function Derivative
- Update Rule 

### Regularized Method for Regression
- Regularize coefficients
- Penalizes the coefficients 
- Robustness to collinearity (correlation)
- Ridge Regression
- Lasso Regression
- Elastic Net Regression

### Polynomial Regression
- Using linear models trained on non-linear functoions
- Trandformation of higher degrees functions to linear functions

### Non-Linear Relationships
- Decision Trees
- Random Forest (Ensemble)
- Ada Boost (Ensemble)
- Feature Importance Review


### Pre-Processing Data
- Standardization
- Mean Removal
- MinMax
- Scaling attributes to a range
- Update attribute to binary
- Categorical attributes

### Variance Bias
- Validation Curve
	- validation and training score vs varying hyperparameters
	- underfit vs overfitting based on hyperparameters
	- Estimators (bias, variance, noise)
- Learning Curve
	- validation and training score vs number of training samples

### Cross Validation
- holdout method CV
- k-fold CV
- Stratified k-fold
- Metrics
- Mean Score and Std deviation 


## Evaluation
- Residual Analysis
- Mean Squared Error
- Coefficient of Determination
- R2 Score

## Notes
- Outliers are the main issue affecting a Linear Regression model.
- RANSAC regression used to target outliers

## Resources

#### Pair Plots
- https://mylearningsinaiml.wordpress.com/2018/11/21/pair-plots/
- https://vita.had.co.nz/papers/gpp.pdf
- http://zerosnones.net/2d-scatter-plot/

#### Correlation Analysis
- http://sphweb.bumc.bu.edu/otlt/MPH-Modules/BS/BS704_Multivariable/BS704_Multivariable5.html
- https://www.statisticshowto.datasciencecentral.com/probability-and-statistics/correlation-analysis/
- https://www.dummies.com/education/math/statistics/how-to-interpret-a-correlation-coefficient-r/
- https://statistics.laerd.com/statistical-guides/pearson-correlation-coefficient-statistical-guide.php


