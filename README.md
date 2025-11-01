# Income Prediction Using Naive Bayes Classifier

## Overview
This project aims to predict whether a person earns **more than $50K per year** based on demographic and employment data.  
The model uses the **Naive Bayes Classification Algorithm**, a probabilistic machine learning technique based on Bayes’ Theorem and the assumption of feature independence.

---

## Dataset
The dataset contains demographic and work-related attributes such as:

- Age  
- Workclass  
- Education  
- Occupation  
- Hours-per-week  
- Marital-status  
- Capital gain/loss  
- Native country  
- **Income (target variable)** → `<=50K` or `>50K`

##  Project Workflow

### 1. Import Libraries
Imported required Python libraries such as **NumPy**, **Pandas**, **Matplotlib**, **Seaborn**, and **Scikit-learn**.

### 2. Import Dataset
Loaded the dataset using **Pandas** and performed basic inspection to understand data types and structure.

### 3. Exploratory Data Analysis (EDA)
- Checked for missing values and duplicates  
- Visualized distributions of categorical and numerical features  
- Explored correlations and relationships

### 4. Declare Feature Vector and Target Variable
Separated independent variables (`X`) and the dependent variable (`y`).

### 5. Split Data
Split the dataset into **training** and **testing** sets using `train_test_split()`.

### 6. Feature Engineering
Encoded categorical variables using **Label Encoding** or **One-Hot Encoding**.

### 7. Feature Scaling
Scaled numerical features using **StandardScaler** to normalize data.

### 8. Model Training
Trained the **Naive Bayes Classifier** (Gaussian or Multinomial) on the training set.

### 9. Predict Results
Generated predictions using the trained model.

### 10. Model Evaluation
Evaluated model performance using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)  
- ROC-AUC Curve  
- k-Fold Cross Validation

---

##  Conclusion
The **Naive Bayes Classifier** provides a simple yet effective approach for income classification.  
Despite its simplicity, it demonstrates strong baseline performance and interpretability.


---
