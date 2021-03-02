# Bank Customer Deposit Prediction

Used Decision Tree Classifier to predict if a customer is going to make a deposit or not.

Steps:
  1) Importing Libraries
  2) Reading Bank Data
  3) Checking for Null Values
  4) Checking for Duplicates
  5) Checking for Outliers and Removing them
  6) Label Encoding of Categorical Fields
  7) Splitting Data into X(independent) and Y(dependent) variable
  8) Splitting Data into Train and Test
  9) Feature Scaling
  10) Build Decision Tree Model:
        a) using CART(Gini) splitting criteria
        b) using C4.5(Entropy) splitting criteria
  11) Choosing the depth with better Score
  12) Choosing the splitting method with better Score
  13) Predicting the value of Y with test data
  14) Confusion Matrix
  15) Classification Report
  16) ROC and AUC Curve
