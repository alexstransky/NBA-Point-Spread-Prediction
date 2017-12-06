# NBA-Point-Spread-Prediction
Databases and Data Visualization Project

**CSVs:**

*bigspreaddata.csv*
 - Contains the raw data used to generate all models

*resultsDiff.csv*
 - Contains the results of all of the regression models
 - Used for Regression Results notebook

*resultsClass.csv*
 - Contains the results of all of the classification models
 - Used for Class Results notebook

**Modeling Notebooks:**

*EDA and PCA.rmd*

 - Contains the initial reading of the bigspreaddata.csv
 - Demonstrates initial exploratory data analysis and principal component analysis
 - Must be run prior to initializing any of the Regression or Classification modeling notebooks

*Linear Regression and Set Generation.rmd*
 - Contains linear regression modeling

*Random Forest Regression.rmd*
 - Contains random forest regression modeling

*XGBoost Regression.rmd*
 - Contains XG Boost regression modeling

*LASSO Regression.rmd*
 - Contains LASSO regression modeling

*Classification.rmd*
 - Contains all classification models that were produced
 
**Results Notebooks:**
 - These contain the generation of all plots used for the final project
 - These notebooks can be run solely using the resultsDiff.csv or resultsClass.csv
 - Do not require running the EDA and PCA notebook

*Regression Results.rmd*
 - Contains the results and analysis of all regression models built to predict final point spread

*Class Results.rmd*
 - Contains the results and analysis of all classification models built to predict winners
