# Food Delivery Time Prediction 🍔🚴‍♂️

## 📌 Project Overview
This project aims to predict whether a food delivery will be **Fast** or **Delayed** using machine learning techniques.  
It follows a complete end-to-end ML workflow including data preprocessing, feature engineering, model training, evaluation, and comparison.

The project is implemented as a **binary classification problem** and follows the provided assignment guidelines strictly.

---

## 🎯 Objective
To classify food delivery orders into:
- **Fast Delivery (0)**
- **Delayed Delivery (1)**

based on factors such as distance, traffic conditions, weather conditions, order details, and ratings.

---

## 🗂️ Dataset Description
The dataset includes the following types of information:
- Customer and restaurant locations
- Weather conditions
- Traffic conditions
- Delivery person experience
- Order priority and order time
- Order cost, tip amount, and ratings
- Delivery time (used to create the target variable)

---

## ⚙️ Project Workflow

### 🔹 Phase 1: Data Preprocessing
- Loaded and explored the dataset
- Handled missing values using:
  - Mean imputation for numerical features
  - Mode imputation for categorical features
- Encoded categorical variables using **Label Encoding**
- Engineered a new feature **Distance** using the **Haversine formula**
- Created a binary target variable (Fast / Delayed)
- Applied **feature scaling** using `StandardScaler`

---

### 🔹 Phase 2: Model Building
The following machine learning models were trained and evaluated:
- **Gaussian Naive Bayes**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree Classifier**

Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

---

### 🔹 Phase 3: Model Comparison & Evaluation
- Compared model performance using accuracy bar plots
- Visualized confusion matrices
- Plotted ROC curves and calculated AUC
- Analyzed strengths and weaknesses of each model

---

## 📊 Results & Insights
- **KNN** achieved the best balance between accuracy and recall after feature scaling
- **Decision Tree** provided good interpretability but required depth control to avoid overfitting
- **Naive Bayes** served as a strong baseline with fast training time
- Distance and traffic conditions were found to be major factors affecting delivery delays

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Repository Structure
