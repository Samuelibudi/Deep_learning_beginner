Logistic Regression with TensorFlow: Predicting Customer Churn

Objective:
Train a logistic regression model to predict customer churn using a structured dataset.

Dataset:
Telco Customer Churn Dataset

Steps:
Load the dataset into a Pandas DataFrame.
Preprocess the data:
Handle missing values.
Convert categorical variables to numerical (one-hot encoding).
Normalize numerical columns.
Build a logistic regression model using TensorFlow/Keras with a single neuron output (sigmoid activation).
Train the model and use Binary Cross-Entropy as the loss function.
Evaluate performance using accuracy and AUC-ROC.
Set a target metric: Achieve at least 80% accuracy and an AUC-ROC of 0.85 on the test set.

Archieved Accuracy: 81% AUC: 86%