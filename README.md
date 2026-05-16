# CISC483-683-Final
This analysis of various clustering and classification methods was done for the final project in CISC-483/CISC-683. Our dataset can be found [here](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) and is a transaction record for purchases made through Brazilian ecommerce platform Olist between 2016 and 2018. The goal of this project was to determine what customer features in this dataset had the highest influence on customer retention rates in order to allow businesses to build better, data informed customer retention strategies.

We compared 2 clustering algorithms, k-Means and DBSCAN, and 2 classification algorithms, logistic regression and XGBoost. We found that DBSCAN on RFM features and XGBoost provided the best results.

## How to Run
All code is encapsulated in Jupyter notebooks. Data is included in its original form and in the merged, cleaned form. There is also a file for the RFM features. Therefore, code can be run in any notebook independently of the other notebooks and without having to import and preprocess data beforehand.

Package imports are also included, though you may have to install dependencies.
