![Banner](https://github.com/thetechleila/Financial-Fraud-EDA-and-Classification-Algorithms/blob/main/images/Financial%20Fraud%20Detection%20Banner.png)
___

# Project Overiew

This project examines a synthetic dataset of bank transactions to see which strategies work best to successfully capture as many fraudulent transactions as possible while minimizing false positives.

Fraud will be identified through focusing on specific features such as transaction type, account balances, and the pre-existing "IsFraud" label where 0 = NotFraud and  1 = IsFraud.

The project is broken down into 3 stages, each stored in their own Jupyter Notebook in the folder labeled "code."

## **Stage 1:** *EDA*

Univariate, bivariate, and multivariate analysis accompanied by data visualizations to provide insight into the raw, unprocessed dataset.

## **Stage 2:** *Data Preprocessing, Data Cleaning, Data Wrangling*

Dropping of unnecessary columns, removal of any missing values and null values, removal of outliers, correction of incorrectly formatted data, creation of new dataframes with processed data

## **Stage 3:** *Model Creation & Evaluation* 

* **Model Evaluation:** Creation of train-test-splits followed by implementation of supervised learning method(s). Hyperparameter tuning follows by the training of the initial classifer via Random Search. The F1 Score and visualizations are utilized to compare and assess model performances after determining optimal hyperparameters and generating new predictions.

Model Evaluation of the Logistic Regression, Naive Bayes and the K-Nearest Neighbor Classifiers are located in model_01.ipynb 

Model Evaluation of the Random Forest and the Gradient Boosting Classifier are located in [model_02.ipynb]()


* **Linear Regression:** Implemented to understand the linear relationships between the target variable and predictor variables & the linear relationships among other features.

___
## Tools

* Python
* NumPy for mathmatical & statistical operations
* Pandas for data manipulation
* SciPy for statistics, linear algebra, optimization
* Matplotlib & Seaborn for data visualization
* Scikit-learn for machine learning and data processing
* Statsmodels for statistical data exploration
* Jupyter Notebooks

___

## **Data Overview**

___
### *Numerical Features*

* **Step:** A unit of time that represents hours in the dataset.

* **Amount:** The amount of money transferred 

* **OldBalanceOrg:** The origin accounts balance before the transaction 

* **NewBalanceOrg:** The origin accounts balance after the transaction 

* **OldbalanceDest:** The destination account's balance before the transaction 

* **NewbalanceDest:** The destination account's balance after the transaction 

* **IsFlaggedFraud:** A “naive” model that simply flags a transaction as fraudulent if it is greater than 200,000 (note that this currency is not USD) 

* **IsFraud:** Was this simulated transaction actually fraudulent? In this case, we consider “fraud” to be a malicious transaction that aimed to transfer funds out of a victim’s bank account before the account owner could secure their information. 

___
## Categorical Features

* **Type:** The type of transaction 

* **NameOrig:** The origin account name

* **NameDest:** The destination account name 