# Logistic Regression and K-Nearest Neighbour Models for Breast Cancer Diagnosis

For this project, Logistic Regression and K-Nearest Neighbour models are compared by predicting if a patient has malignant or benign breast cancer cells. Scikit Learn's LogisticRegression and KNeighborsClassifier classes are used.

## Dataset and Library
Scikit Learn's LogisticRegression and KNeighborsClassifier classes were used to create the models.

The dataset consisted of 569 rows by 32 columns of patient information, including the label which was the Malignant or Benign diagnosis.
Please find the dataset from the University of California Irvine's Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

## Results
Based on the Classification Report, the Logistic Regression Model achieved an overall accuracy of 98%, with a high precision and recall. Similarly, the K-Nearest Neighbour Model achieved an accuracy of 97% with comparable precision and recall as well. 

However, the K-Nearest Neighbour model did perform dangerously worse by incorrectly misclassifying 5 malignant patients as benign. This is a very bad false negative, as the individuals would forego treatment believing they are fine. Overall though, both model performed similarly well on the test set.

Please visit the following link for more details: https://hjmok.github.io/josephmok_portfolio/#/BC 
