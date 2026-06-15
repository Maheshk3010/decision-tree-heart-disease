# Decision Tree Classification - Heart Disease Dataset

## 📌 Project Overview
This project demonstrates the implementation of a Decision Tree Classification model on the Heart Disease dataset. The goal is to predict whether a patient has heart disease based on various medical attributes.

---

## 📊 Dataset
- Dataset: Heart Disease Dataset
- File: heart_disease.xlsx
- Sheet Used: Sheet 2 (actual dataset)

---

## 🔍 Steps Performed

### 1. Data Preparation
- Loaded dataset using pandas
- Selected correct sheet for analysis

### 2. Exploratory Data Analysis (EDA)
- Checked data types and summary statistics
- Visualized data using histograms and correlation heatmap
- Checked for missing values

### 3. Feature Engineering
- Converted categorical variables into numerical format using one-hot encoding
- Cleaned inconsistent values in dataset

### 4. Model Building
- Split data into training and testing sets
- Applied Decision Tree Classifier

### 5. Model Evaluation
- Evaluated model using accuracy and classification report

### 6. Hyperparameter Tuning
- Tuned parameters such as max_depth and min_samples_split to improve performance

### 7. Visualization
- Visualized the Decision Tree structure using plot_tree

---

## 📈 Results
- The model achieved good accuracy on test data
- Hyperparameter tuning improved model performance

---

## 💡 Conclusion
The Decision Tree model effectively predicts heart disease based on input features. Proper data preprocessing and tuning significantly improve the model performance.

---

## ❓ Interview Questions

### 1. Common Hyperparameters
- max_depth: Controls tree depth and prevents overfitting
- min_samples_split: Minimum samples required to split
- criterion: Splitting method (gini/entropy)

### 2. Label Encoding vs One-Hot Encoding
- Label Encoding: Assigns numeric values to categories
- One-Hot Encoding: Creates binary columns for each category

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔗 GitHub Repository
https://github.com/Maheshk3010/decision-tree-heart-disease

## ▶️ How to Run
1. Open notebook in Google Colab
2. Upload dataset file
3. Run all cells

## 👤 Author
Mahesh kale
