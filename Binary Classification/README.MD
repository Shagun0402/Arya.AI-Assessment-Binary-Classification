Binary Classification  of Dataset - Arya.AI Assessment for Data Scientist role

Files:

1. [dataset](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/tree/main/Binary%20Classification/dataset) - includes training and test data
3. [EDA - Accuracy, Precision, Recall](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/blob/main/Binary%20Classification/EDA%20-%20Accuracy%2C%20Precision%2C%20Recall%20.ipynb) - this file performs EDA and visualizes the accuracy, precision and recall for all the selected models.
2. [Data Pre-Processing](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/blob/main/Binary%20Classification/Data%20Pre-processing.ipynb) - exploratory data analysis, feature selection, data normalization, model training, model selection
3. [Model_Performance](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/blob/main/Binary%20Classification/Model_Performance.ipynb) - Based on data exploration, this file shows the performance of all the models
4. [Predictions](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/blob/main/Binary%20Classification/Predictions.ipynb) - Based on the analysis, It shows the predictions XGBoost model makes on test data set. 
5. [requirements.txt](https://github.com/Shagun0402/Arya.AI-Assessment-Binary-Classification/blob/main/Binary%20Classification/requirements.txt) - this file is defines the versions for all the external libraries used for this project


**Steps involved in the assessment:** 

    I have performed basic EDA on the training data to get insights on data. 

    For feature selection, I have used Random Forest classifier to find the feature importance.

    Based on the feature importance, I have selected 30 top features for model training. 

    In order to achive numerical stability (because the data is highly sparse and continuous), I have applied StandardScaler to normalize the data.

**Model used for training the data:**
    1. Random Model
    2. Logistic Regression
    3. Naive- Bayes Classification
    4. Support Vector Machine - using l2 penalty
    5. K- Nearest Neighbors Classification
    6. Decision Tree Classification
    7. Random Forest Classification
    8. XGBoost Classification

**The valuation Metrics for model selection:**
    1. Accuracy
    2. Precision
    3. Recall
    4. Log-Loss
    5. AUC Score

I have used the above mentioned metrics to evaluation the model performances and based on the the metric scores concluded that the best model for the binary classification task is: **XGBOOST Model**.


