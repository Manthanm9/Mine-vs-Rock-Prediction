# Mine-vs-Rock-Prediction

This repository contains a Jupyter Notebook (mine-vs-rock-prediction.ipynb) that demonstrates the use of logistic regression for classifying sonar signals as either rocks or mines.

## Dataset
The dataset used in this project consists of sonar readings, with each reading represented by 60 features. The target variable contains the labels 'R' for rocks and 'M' for mines. The notebook provides code to load the dataset and perform basic exploratory data analysis, including examining the shape, summary statistics, and value counts of the dataset.

## Data Preprocessing
Before training the model, the notebook performs data preprocessing steps. The features and labels are separated into two variables (X and y). The features are stored in a pandas DataFrame, while the labels are stored in a Series.

## Model Training
The logistic regression algorithm is used to train a classification model on the provided dataset. The notebook utilizes the LogisticRegression class from the scikit-learn library. The model is trained on the training data using the fit method.

## Model Evaluation
To evaluate the model's performance, the notebook calculates the accuracy on both the training and testing datasets. The accuracy score is computed using the accuracy_score function from scikit-learn. The notebook displays the accuracy on the training and testing data.

## Making Predictions
In addition to evaluating the model's performance, the notebook provides code to make predictions on new, unseen data. An example input data point is provided, and the trained model predicts whether it belongs to the "Rock" or "Mine" class. The prediction is printed, along with a corresponding message indicating the object's classification.
