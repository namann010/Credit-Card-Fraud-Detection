# Credit Card Fraud Detection

## Overview
This project focuses on identifying fraudulent credit card transactions using machine learning. Because fraud datasets are highly imbalanced, standard accuracy is not a reliable metric. This project utilizes a Random Forest classifier to optimize for Precision and Recall, minimizing false positives while successfully catching anomalous transactions.

## Results
The model was tested on an unseen test set with the following core metrics:
* **Precision:** 96.08% 
* **Recall:** 89.09% 

Out of over 38,000 normal transactions, the model only falsely flagged 2, ensuring a frictionless experience for legitimate users while maintaining tight security.

## Technologies Used
* Python
* Random Forest Classifier
* Pandas & Scikit-Learn
* Data Visualization (Seaborn/Matplotlib)

## Dataset
The data used for this project is the standard Credit Card Fraud Detection dataset, which contains PCA-transformed features to protect user confidentiality.
