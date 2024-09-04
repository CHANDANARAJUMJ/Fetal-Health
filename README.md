# Fetal-Health-Classification

This project focuses on classifying fetal health status through a comprehensive machine learning approach, involving data preprocessing, oversampling techniques, dimensionality reduction, and model evaluation.

### 1. Data Preprocessing:
   - The dataset, containing various medical indicators related to fetal health, is initially cleaned to remove any inconsistencies or missing values.
   - Standardization is applied using StandardScaler to ensure that all features contribute equally to the model.

### 2. SMOTE Technique:
   - **SMOTE (Synthetic Minority Over-sampling Technique)** is employed to address class imbalance in the dataset. This technique generates synthetic samples for the minority class, helping to create a more balanced training set and improving model performance.

### 3. PCA Analysis:
   - After applying SMOTE, **Principal Component Analysis (PCA)** is performed to reduce the dimensionality of the dataset. This step helps in capturing the most significant features while minimizing noise, which enhances the efficiency of the models.

### 4. Model Prediction:
   - Several machine learning models are trained on the processed data, including:
     - **Random Forest Classifier**
     - **Decision Tree Classifier**
     - **Logistic Regression**
     - **K-Nearest Neighbors (KNN)**
     - **Support Vector Classifier (SVC)**
   - Each model is evaluated based on various performance metrics, such as accuracy, precision, recall, and F1-score.

### 5. Results:
   - Among the five models, the Random Forest demonstrated the highest accuracy and overall effectiveness in predicting fetal health. Detailed performance metrics and visualizations (e.g., confusion matrices) are provided to highlight the strengths and weaknesses of each model.
     
### Publication:
I have published a paper on this work titled "Optimizing Fetal Health Classification using PCA and SMOTE Techniques," where I delve deeper into the methodology and findings. This project serves as a practical implementation of the concepts discussed in the paper.


