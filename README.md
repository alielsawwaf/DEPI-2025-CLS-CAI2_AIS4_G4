Bank Customer Churn Prediction

![image](https://github.com/user-attachments/assets/bf017cd9-dcbf-4860-947d-aa8aa7d77366)

The project involves the following steps:
Data Collection: Gather data on bank customers, including their demographics, account details, and transaction history.

Data Preprocessing: Clean and preprocess the data to handle missing values, outliers, and categorical variables.

Exploratory Data Analysis (EDA): Perform EDA to understand the distribution of data, identify patterns, and visualize relationships between features.

Feature Engineering: Create new features or transform existing ones to improve the predictive power of the model.

Model Building: Train various machine learning models to predict customer churn and evaluate their performance.

Model Evaluation: Assess the models using appropriate metrics and select the best-performing model.

Deployment: Deploy the model to a production environment where it can be used to make predictions.

Dashboard: Creation of dashboard visual with matplotlib to give more insights on the prediction made by the model

![image](https://github.com/user-attachments/assets/7b88a7db-5045-4be2-accb-e1e8946aba2a)

![image](https://github.com/user-attachments/assets/6567de66-1b5f-40ec-a051-733e61c3af12)

Dealing with unbalanced data:

![image](https://github.com/user-attachments/assets/d1cdb697-a051-4547-9320-d7ca26fcadfa)

Apply SMOTe to balance Data:

![image](https://github.com/user-attachments/assets/ebe7f0a3-3efc-4f4d-8296-811d55819f62)
![image](https://github.com/user-attachments/assets/1d3de216-d9cf-4337-9864-6c0314a698fc)

Evaluating different Model:
![image](https://github.com/user-attachments/assets/36c2226b-fd22-45c9-9ccc-121a981b0db1)

Model: Logistic Regression
Metric              Train       Test
---------------------------------------------
Accuracy            0.7146      0.7144
Precision           0.7188      0.7185
Recall              0.7050      0.7050
F1-Score            0.7118      0.7117
ROC-AUC             0.7800      0.7825
=============================================
=============================================

Model: Decision Tree
Metric              Train       Test
---------------------------------------------
Accuracy            1.0000      0.8352
Precision           1.0000      0.8363
Recall              1.0000      0.8336
F1-Score            1.0000      0.8350
ROC-AUC             1.0000      0.8352
=============================================
=============================================

Model: Random Forest
Metric              Train       Test
---------------------------------------------
Accuracy            0.9999      0.8858
Precision           0.9998      0.8927
Recall              1.0000      0.8770
F1-Score            0.9999      0.8847
ROC-AUC             1.0000      0.9557
=============================================
=============================================

Model: SVM
Metric              Train       Test
---------------------------------------------
Accuracy            0.7943      0.7781
Precision           0.8077      0.7911
Recall              0.7727      0.7558
F1-Score            0.7898      0.7730
ROC-AUC             0.8736      0.8684
=============================================
=============================================

Model: Gradient Boosting
Metric              Train       Test
---------------------------------------------
Accuracy            0.8731      0.8534
Precision           0.8815      0.8689
Recall              0.8620      0.8324
F1-Score            0.8717      0.8503
ROC-AUC             0.9454      0.9347
=============================================
=============================================

Model: K-Nearest Neighbors
Metric              Train       Test
---------------------------------------------
Accuracy            0.8967      0.8481
Precision           0.8457      0.7986
Recall              0.9705      0.9309
F1-Score            0.9038      0.8597
ROC-AUC             0.9767      0.9216
=============================================
=============================================

Model: Naive Bayes
Metric              Train       Test
---------------------------------------------
Accuracy            0.7225      0.7169
Precision           0.7411      0.7272
Recall              0.6840      0.6943
F1-Score            0.7114      0.7103
ROC-AUC             0.8011      0.8029
=========================================


AUC:
![image](https://github.com/user-attachments/assets/11a17aa6-331e-46ad-bd71-c5e9aab4232b)






