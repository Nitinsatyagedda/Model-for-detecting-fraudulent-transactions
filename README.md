# Model-for-detecting-fraudulent-transactions
This project involves developing a machine learning model to predict fraudulent transactions for a financial company. The dataset contains transaction records, and the goal is to identify which transactions are fraudulent.
# Project Description
This project involves developing a predictive model to identify fraudulent transactions using a dataset provided in CSV format. The goal is to leverage both statistical analysis and machine learning techniques to build a robust fraud detection system. The insights gained from the model will help develop actionable plans to mitigate fraudulent activities.
# Dataset
The dataset used consists of 6,362,620 rows and 10 columns, and the task is to identify which transactions are fraudulent.
The dataset file is too large to store in the github. So attached the column explanation file.
# Pre-requsites
Install the following packages to run the project.
1. pip install pandas
2. pip install seaborn 
3. pip install matplotlib 
4. pip install scikit-learn 
5. pip install imbalanced-learn 
# Usage
1. Load the data
2. Preprocess or clean the data
3. Split the data into training and testing sets
4. Train the model
5. Evaluate the model
6. Analyze the importance of each feature in predicting fraud
# Explanation
1. Load the data
   Import the dataset using pandas to manupulate with the data.
2. Preprocess or clean the data
   Steps in cleaning the data
   1. Checking the null values.
   2. Coverting catogorical to numerical values.
   3. Removing unwanted features.
   4. checking and solving the class imbalance.
3. Split the data into traning and testing sets
   After the class balancing, with that data spliting into traning and testing X_train, y_train, X_test, y_test
4. Train the model
   Random forest model is taken and trained on this dataset.
5. Evaluate the model
   Evaluated the trained model by using some evaluation metrics like accuracy, Precison etc
   The accuracy of this model is 0.992  
