# Project overview
The primary objective of this project is to harness the capabilities of machine learning to detect and predict fraudulent activities within online payment transactions. By meticulously examining historical payment data, our goal revolves around constructing a predictive model tailored to efficiently and precisely identify fraudulent transactions. Implementing such a model is vital for bolstering security protocols and substantially mitigating financial losses linked to online payment fraud. Through this endeavor, we aim to navigate and address the complexities of online payment systems, ensuring a safer transaction environment for businesses and individuals alike by significantly reducing the incidence of fraud.

## Our goal is to detect fraud early and accurately to improve transaction safety for our customers.


# Questions 
- How can historical transaction data be used to predict fraud activities?
- What features are most indicative of fraud transactions?
- How do different machine learning models compare in their ability to detect online payment fraud?


# Dataset 
- Name: Online Payment Fraud Detection
- Link: https://www.kaggle.com/datasets/jainilcoder/online-payment-fraud-detection 


## Main dataset issues
- Imbalanced Classes: The dataset contains a significantly higher number of legitimate transactions compared to fraudulent ones, which could bias the model.
- Missing Values: Some columns contain missing values, which require appropriate handling to maintain dataset integrity.
- Feature Engineering: The relationship between features and the target variable (fraudulent or not) may not be linear or easily distinguishable without transforming or creating new features.

## Solutions for the dataset issues
- To address imbalanced classes, techniques such as SMOTE (Synthetic Minority Over-sampling Technique) or undersampling the majority class were considered.
- Missing values were handled by imputation (e.g., using median values for numerical features) or by removing rows/columns with a significant amount of missing data.
- Feature scaling was performed using StandardScaler to normalize the range of the data, thus improving model performance.


# Conclussions
...

# Next steps
...
