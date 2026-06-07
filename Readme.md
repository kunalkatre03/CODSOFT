# CODSOFT Machine Learning Internship

This repository contains all the tasks completed during my Machine Learning Internship at CodSoft. The projects demonstrate the application of Machine Learning, Data Analysis, and Natural Language Processing techniques to solve real-world problems.

## Internship Tasks

### ✅ Task 1: Movie Genre Classification

Developed a Machine Learning model to predict movie genres based on plot summaries using Natural Language Processing (NLP).

**Key Features:**

* Text preprocessing and feature extraction using TF-IDF
* Genre prediction from movie descriptions
* Logistic Regression classifier
* Model evaluation and performance analysis
* Custom genre prediction support

**Technologies Used:**

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorizer
* Logistic Regression

**Result:**

* Achieved approximately **57.94% accuracy** on the test dataset.

---


### ✅ Task 2: Credit Card Fraud Detection

Developed a Machine Learning model to detect fraudulent credit card transactions using customer and transaction-related information. The objective of this project was to classify transactions as legitimate or fraudulent and help identify suspicious activities that could indicate financial fraud.

**Project Workflow:**

* Loaded and explored large-scale transaction datasets containing over 1.2 million records.
* Performed data cleaning and preprocessing.
* Selected relevant transaction and customer features for model training.
* Encoded categorical variables such as transaction category, customer gender, and occupation using Label Encoding.
* Handled a highly imbalanced dataset where fraudulent transactions represented less than 1% of total transactions.
* Built and trained a Random Forest Classifier to identify fraudulent transactions.
* Evaluated model performance using Accuracy Score, Confusion Matrix, and Classification Metrics.

**Features Used:**

* Transaction Category
* Transaction Amount
* Customer Gender
* City Population
* Customer Occupation
* Customer Location Coordinates
* Merchant Location Coordinates

**Technologies Used:**

* Python
* Pandas
* NumPy
* Scikit-learn
* Label Encoding
* Random Forest Classifier
* Jupyter Notebook

**Model Performance:**

* Achieved approximately **99.74% accuracy** on the test dataset.
* Successfully identified fraudulent transactions with high precision.
* Evaluated performance using a confusion matrix to analyze correctly classified and misclassified transactions.

**Confusion Matrix Results:**

```text
Actual Legitimate → Predicted Legitimate : 553,161
Actual Legitimate → Predicted Fraud      : 413

Actual Fraud → Predicted Legitimate      : 1,043
Actual Fraud → Predicted Fraud           : 1,102
```

**Key Learning Outcomes:**

* Data preprocessing and feature engineering
* Handling imbalanced datasets
* Categorical data encoding
* Fraud detection using Machine Learning
* Random Forest implementation
* Model evaluation and performance analysis
* Real-world financial transaction analytics

**Result:**

* Built an effective fraud detection system capable of distinguishing between legitimate and fraudulent transactions.
* Achieved high predictive performance and demonstrated the practical application of Machine Learning in financial security and fraud prevention.
### ✅ Task 3: Customer Churn Prediction

Developed a Machine Learning model to predict customer churn for a banking institution. The objective was to identify customers who are likely to leave the bank based on demographic and account-related information.

**Key Features:**

* Data preprocessing and cleaning
* Handling categorical variables using Label Encoding and One-Hot Encoding
* Feature selection and transformation
* Customer churn prediction using Random Forest Classifier
* Model evaluation using Accuracy Score and Classification Metrics

**Technologies Used:**

* Python
* Pandas
* NumPy
* Scikit-learn
* Label Encoding
* One-Hot Encoding
* Random Forest Classifier

**Features Used:**

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Membership Status
* Estimated Salary

**Result:**

* Achieved approximately **86.6% accuracy** on the test dataset.
* Successfully identified customers likely to leave the bank.
* Demonstrated the practical application of Machine Learning in customer retention and business analytics.

---


## Repository Structure

```text
CODSOFT/
│
├── Task1_Movie_Genre_Classification/
│
├── Task2_Credit_Card_Fraud_Detection/
│
├── Task3_Customer_Churn_Prediction/
│
└── README.md
```

## About

This repository serves as a collection of projects completed during the CodSoft Machine Learning Internship. Each task focuses on solving practical Machine Learning problems using industry-standard tools and techniques.

## Author

Kunal

Machine Learning Intern at CodSoft
