# credit-risk-classification

An overview of the analysis: the purpose of this exercise was to train and analyze a model based on loan risk. The data used in this assignment was stored in a csv and required importing the information into a dataframe. After splitting the data and fitting it to a logistic regression model, we discovered the results below. 

The results: Using a bulleted list, describe the accuracy score, the precision score, and recall score of the machine learning model.
Original Data
- Accuracy: 99%
- Precision: Healthy loans = 100%. High-risk loans = 87%
- Recall: Healthy loans = 100%. High risk loaks = 89%

Resampled Data
- Accuracy: 100%
- Precision: Healthy loans = 100%. High-risk loans = 87%
- Recall: Healthy loans = 100%. High risk loaks = 100%

A summary: Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning.

Both models resulted in higher accuracy scores and are good predictors of healthy vs high-risk loans. However, the recall scores from Machine Learning Model 2 truly separates itself. If a recommendation were to be made, I would suggest going with Machine Learning Model 2 since the quality of the results were better and it gives the user a better confidence in loan application decision making. 