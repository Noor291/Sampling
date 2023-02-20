# Sampling Assignment

## Aim

This assignment aims to identify the best sampling technique for a highly imbalanced dataset by comparing the performance of seven different machine learning models.

## Dataset

The dataset used in this project is Credit Card Fraud Detection dataset, which is highly imbalanced, with the majority class accounting for 95% of the samples. To address this issue, the Synthetic Minority Over-sampling Technique (SMOTE) was used.

## Sampling Techniques
- Simple Random Sampling
- Cluster Sampling
- Systematic Sampling
- Stratified Sampling
- Convenience Sampling


## Machine Learning Models

- Decision Tree
- K-Nearest Neighbors
- Logistic Regression
- Support Vector Machine
- Random Forest 

## Results

The performance of each model was evaluated using metrics such as accuracy, precision, recall, and F1-score.

| MODEL NAME             | Random Sampling | Cluster Sampling    | Systamatic Sampling | Stratified Sampling |Convenience Sampling
|------------------------|-----------------|---------------------|---------------------|---------------------|--------------------
| Decision Tree          | 85.57           | 95.37               | 70.0                | 90.83               |99.0
| KNN                    | 72.16           | 79.63               | 40.0                | 80.79               |99.0
| LogisticRegression     | 86.60           | 93.05               | 80.0                | 92.14               |98.0
| SVM                    | 76.29           | 67.60               | 60.0                | 70.74               |99.0
| Random Forest          | 98.97           | 99.53               | 80.0                | 100.0               |99.0

## Conclusion

Stratified Sampling with Random Forest Classifier gives the highest efficiency. 
