# Python-AI-Wine-Classification-Algorithms

This project is about Wine Classification using multiple algorithms like Random Forest, Logistic Regression and more. 
The first step is data exploration to import necessary libraries. Then load the dataset that was taken from online cleaned dataset as a sample dataset. Then find data types and unique values. Then print out the summary of dataset based on mean etc.
The second step is to perform Exploratory Data Analysis like finding missing values.
The third step is data preprocessing to check duplicate rows.
The fourth step is data manipulation to train, test and split dataset. Also I used label noise to make sure when running the algorithms will be able to handle noise making sure the values won't change too much everytime I run to get the precision.
The fifth step is feature selection like checking number of variance etc.
The sixth step is modeling using random forest with controlled complexity. It is trained to check the accuracy F1 score, actual labels and predicted labels. Report is gathered and displayed in Confusion Matrix, Predicted Class, and Actual Class. 
The seventh step is AUC-ROC is performed to check the False Positive Rate, True Positive Rate and display in Multiclass AUC-ROC Curve. Feature importances of Random Forest is also shown.
The eight step is simulate noisy test data weighted in accuracy and F1 score with noise.
The ninth step is tuning estimators to check the number of estimators and compare different estimators.
The tenth step is displaying final evaluation summary using estimators, accuracy and F1-Score.
The eleventh step is K-Nearest Neighbors (KNN) calculating the weighted accuracy, F1-score and displaying the report. Then KNN confusion matrix is made in heatmap for the predicted and actual labels. Then ROC-AUC is made displaying the curve based on dataset.
The twelfth step is Logistic Regression calculating the weighted accuracy, F1-score and displaying the report. Then Logistic Regression confusion matrix is made in heatmap for the predicted and actual labels. Then ROC-AUC is made displaying the curve based on dataset.
The thirteenth step is XGBoost calculating the weighted accuracy, F1-score and displaying the report. Then XGBoost confusion matrix is made in heatmap for the predicted and actual labels. Then ROC-AUC is made displaying the curve based on dataset.
The fourtheenth step is Support Vector Machine (SVM) calculating the weighted accuracy, F1-score and displaying the report. Then SVM confusion matrix is made in heatmap for the predicted and actual labels. Then ROC-AUC is made displaying the curve based on dataset.
The fifteenth step is Multi-Layer Perceptron (MLP) calculating the weighted accuracy, F1-score and displaying the report. Then MLP confusion matrix is made in heatmap for the predicted and actual labels. Then ROC-AUC is made displaying the curve based on dataset.
The sixtheenth step is comparing all algorithm models Random Forest, KNN, Logistic Regression, XGBoost, SVM, and MLP based on accuracy and F1-Score.
