# Football-analysis
Developed a regression model that predict market value of players with MAE =€0.6 using data collected with Web Scraping.

This project has following parts :

Data collection, Data cleaning, Feature engineering, EDA, Train
models, Hyperparameter tuning using grid search, Model evaluation
using Kfold cross validation , Plot learning curves.

Models: linear regression , lasso regression, ridge regression, random
forest regression.(Random forest model outperformed other models and had best performance, so we used it for final prediction.)

This model has **MAE=€0.6M** (which means on average it can predict
players value with €0.6M error) and **R squared = 96%**.