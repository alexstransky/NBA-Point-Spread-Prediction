# NBA-Point-Spread-Prediction
Databases and Data Visualization Project

**CSVs:**
*bigspreaddata.csv*
 - contains the raw data used to generate all models
*resultsDiff.csv*
 - contains the results of all of the regression models
 - used for Regression Results notebook
*resultsClass.csv*
 - contains the results of all of the classification models
 - used for Class Results notebook

**Modeling Notebooks:**
*EDA and PCA.rmd*
 - contains the initial reading of the bigspreaddata.csv
 - demonstrates initial exploratory data analysis and principal component analysis
 - must be run prior to initializing any of the Regression or Classification modeling notebooks
*Linear Regression and Set Generation.rmd*
 - contains linear regression modeling
*Random Forest Regression.rmd*
 - contains random forest regression modeling
*XGBoost Regression.rmd*
 - contains XG Boost regression modeling
*LASSO Regression.rmd*
 - contains LASSO regression modeling
*Classification.rmd*
 - contains all classification models that were produced
 
**Results Notebooks:**
 - these contain the generation of all plots used for the final project
*Regression Results.rmd*
 - contains the results and analysis of all regression models built to predict final point spread
*Class Results.rmd*
 - contains the results and analysis of all classification models built to predict winners
