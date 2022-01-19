Binary Classification  of Dataset - Arya.AI Assessment for Data Scientist role



Steps involved in the assessment: 

I have performed basic EDA on the training data to get insights on data. 

For feature selection, I have used Random Forest classifier to find the feature importance.

Based on the feature importance, I have selected 30 top features for model training. 

In order to achive numerical stability (because the data is highly sparse and continuous), I have applied StandardScaler to normalize the data.

Model used for training the data:
1. Random Model
2. Logistic Regression
3. Naive- Bayes Classification
4. SUpport Vector Machine - using l2 penalty
5. K- Nearest Neighbors Classification
6. Decision Tree Classification
7. Random Forest Classification
8. XGBoost Classification

The valuation Metrics for model selection:
1. Accuracy
2. Precision
3. Recall
4. Log-Loss
5. AUC Score

I have used the above mentioned metrics to evaluation the model performances and based on the the metric scores concluded that the best model for the binary classification task is: XGBOOST Model.



Files:

1. dataset - includes training and test data
3. EDA - Accuracy, Precision, Recall - this file performs EDA and visualizes the accuracy, precision and recall for all the selected models.
2. Data Pre-Processing - exploratory data analysis, feature selection, data normalization, model training, model selection
3. Model_Performance - Based on data exploration, this file shows the performance of all the models
4. Predictions - Based on the analysis, It shows the predictions XGBoost model makes on test data set. 
5. requirements.txt - this file is defines the versions for all the external libraries used for this project

