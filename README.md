# Logistic Regression and K-Nearest Neighbour Models for Breast Cancer Diagnosis

For this project, Logistic Regression and K-Nearest Neighbour models are compared by predicting if a patient has malignant or benign breast cancer cells. 

## Dataset and Library
Scikit Learn's LogisticRegression and KNeighborsClassifier classes were used to create the first two models. In addition, PySpark's LogisticRegression module was used to create a third model.

The dataset consisted of 569 rows by 32 columns of patient information, including the label which was the Malignant or Benign diagnosis.
Please find the dataset from the University of California Irvine's Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

## Results
Based on the Classification Report, the Scikit-Learn Logistic Regression Model achieved an F1-score of 98%, with a high precision and recall. Similarly, the K-Nearest Neighbour Model achieved an F1-score of 97% with comparable precision and recall as well. Lastly, the PySpark Logistic Regression Model comparable achieved a 96% F1-score. 

However, the K-Nearest Neighbour model did perform dangerously worse by incorrectly misclassifying 5 malignant patients as benign. This is a very bad false negative, as the individuals would forego treatment believing they are fine. Overall though, both model performed similarly well on the test set.

Please visit the following link for more details: https://hjmok.github.io/josephmok_portfolio/#/BC 
