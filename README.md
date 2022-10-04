# Telecom Churn Prediction

It is important for subscription services like telecom operators to identify the customers who may be on the verge of exiting their platforms.
Successfully predicting such customers can help the marketing teams at these organisations to provide offers or other inducements to retain them. In this project, Machine learning models are used to predict if a particular customer is on the verge of quitting the service. The final model is converted into a flask app and containarized with docker for easy deployment.

## Data

The dataset used can be found [here](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)


## Exploratory Data Analysis

Exploratory data analysis was performed to gain understanding of the dataset and features available. Refer to (this notebook)[https://github.com/esviswajith95/churn_prediction/blob/master/notebooks/eda.ipynb] for details.

## Modelling

Various models were applied on the datset to select the best model. The best model turned out to be a Logistic Regression model. Refer to (this notebook)[https://github.com/esviswajith95/churn_prediction/blob/master/notebooks/modelling.ipynb] for detailed set up and analysis of models.

## Deployment

The the final model was turned into a web service through a flask app. This is then containarized with docker for easy deployment.

