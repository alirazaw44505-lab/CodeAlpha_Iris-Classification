
 Project Overview
----------------------------------------------------------------------------------------------------------------


This project focuses on classifying Iris flowers into three species — **Setosa**, **Versicolor**, and **Virginica** — using their physical measurements.

A **K-Nearest Neighbors (KNN)** classification model is trained and evaluated using **Scikit-learn**.

The project demonstrates the complete machine learning classification workflow, including **data preprocessing**, **model training**, and **performance evaluation**.

---------------------------------------------------------------------------------------------------------------

 📊 Dataset


**Source:** Kaggle – Iris Dataset

🔹 Features Used
------------------------------------------------------------------------------------------------------------

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

🎯 Target Variable
----
- Species (Setosa, Versicolor, Virginica)

The dataset is loaded from a CSV file and cleaned by removing unnecessary columns (e.g., `Id`).

---

🛠️ Technologies & Libraries Used
------------------------------------------------------------------------------------------------------------


- Python  
- Pandas  
- Scikit-learn  
  - `train_test_split`  
  - `KNeighborsClassifier`  
  - `StandardScaler`  
  - `accuracy_score`  
  - `confusion_matrix`  
  - `classification_report`  

---

⚙️ Project Workflow
------------------------------------------------------------------------------------------------------------


1. Load the Iris dataset from CSV  
2. Remove unnecessary columns  
3. Split data into training and testing sets  
4. Scale features using `StandardScaler`  
5. Train a KNN classifier  
6. Make predictions on test data  
7. Evaluate model performance  
8. Tune the model by testing different values of **K**

------------------------------------------------------------------------------------------------------------

## 📈 Model Evaluation
----

The model performance is evaluated using:
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)

This provides a clear understanding of how well the classifier performs on unseen data.
