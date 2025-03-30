# Financial Fraud Data Set: An Exploratory Data Analysis
___

## Overiew
___
This project involves an exploratory data analysis (EDA) and the usage of machine learning (ML) strategies to find patterns and trends within the raw synthetic financial transaction data, followed by determining which ML technique(s) work best for capturing as many fradulent transactions as possible while minimizing false positives.

___

## Features

* **Exploratory Data Analysis:** univariate, bivariate, and multivariate analysis and data visualizations

* **Data Preprocessing, Data Cleaning, Data Wrangling:** Dropping of unnecessary columns, removal of any missing values and null values, removal of outliers, correction of incorrectly formatted data, creationn of new dataframes with processed data

* **Feature Engineering:** Creation of new features during the machine learning model portion  of the project, transformation of existing features in pursuit of discovering hidden patterns

___

## Machine Learning Models

* **Visualizations:** detailed visualizations of the finanical transaction data including distribution plots, box plots, violin plots, etc.

* **Model Evaluation:** Creating train-test-splits followed by implementation of 2 supervised learning methods. Hyperparameter tuning follows after the training  of the initial classifer via Random Search. The F1 Score and visualizations are utilized to compare and assess model performances after determining optimal hyperparameters and generating new predictions.

* **Linear Regression:** Implemented to understand the linear relationships between the target variable and predictor variables & the linear relationships among other features.

___
## Tools and Libraries

* Python
* NumPy for mathmatical & statistical operations
* Pandas for data manipulation
* Matplotlib & Seaborn for data visualization
* Scikit-learn for machine learning and data processing
* Statsmodels for statistical data exploration

___
## Numerical Variables

* **Step:** A unit of time that represents hours in the dataset.

* **Amount:** The amount of money transferred 

* **OldBalanceOrg:** The origin accounts balance before the transaction 

* **NewBalanceOrg:** The origin accounts balance after the transaction 

* **OldbalanceDest:** The destination account's balance before the transaction 

* **NewbalanceDest:** The destination account's balance after the transaction 

* **IsFlaggedFraud:** A “naive” model that simply flags a transaction as fraudulent if it is greater than 200,000 (note that this currency is not USD) 

* **IsFraud:** Was this simulated transaction actually fraudulent? In this case, we consider “fraud” to be a malicious transaction that aimed to transfer funds out of a victim’s bank account before the account owner could secure their information. 

___
## Categorical Variables

* **Type:** The type of transaction 

* **NameOrig:** The origin account name

* **NameDest:** The destination account name 
