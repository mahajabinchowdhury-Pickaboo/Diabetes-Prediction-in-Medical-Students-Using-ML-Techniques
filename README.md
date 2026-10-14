# Diabetes Prediction in Medical Students Using Machine Learning

## 📌 Project Overview

This project focuses on predicting diabetes among medical students using machine learning techniques. It explores how supervised and unsupervised learning algorithms can be applied to healthcare-related data to identify patterns and predict whether a student has diabetes based on health-related features.

The project follows a complete machine learning workflow, including data exploration, preprocessing, feature scaling, model training, performance evaluation, and model comparison.

## 🎯 Objectives

- Analyze health-related data of medical students.
- Perform exploratory data analysis (EDA) to understand feature distributions and relationships.
- Handle missing values and encode categorical features.
- Train and evaluate multiple machine learning classification models.
- Compare model performance using various evaluation metrics.
- Apply unsupervised learning to identify hidden patterns in the dataset.

## 📊 Dataset Description

The project uses `medical_students_dataset.csv`, which contains health-related information about medical students.

- **Dataset size:** 200,000 rows
- **Features:** Health-related numerical and categorical attributes
- **Target variable:** `Diabetes` (Yes/No)
- **Problem type:** Binary classification

The dataset includes features such as age, height, weight, BMI, temperature, heart rate, blood pressure, cholesterol, gender, blood type, and smoking status.

## ⚙️ Methodology

### 1. Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical feature distributions.
- Generated histograms, box plots, bar charts, and correlation heatmaps.
- Examined the class distribution of the diabetes target variable.

### 2. Data Preprocessing
- Handled missing numerical values using mean imputation.
- Encoded categorical variables for machine learning models.
- Removed invalid or inconsistent entries.
- Applied `StandardScaler` to standardize numerical features.

### 3. Dataset Splitting
- **Training set:** 80%
- **Testing set:** 20%
- Used stratified sampling to preserve the target class distribution.

### 4. Model Training

The following machine learning algorithms were implemented:

**Supervised Learning**
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree Classifier
- Naive Bayes
- Neural Network

**Unsupervised Learning**
- K-Means Clustering

### 5. Model Evaluation

Model performance was analyzed using:
- Accuracy
- Precision
- Recall
- Confusion Matrix
- ROC Curve
- Area Under the ROC Curve (AUC)

The report also discusses R² scores as an additional evaluation measure.

## 📈 Results and Analysis

The project compares the performance of multiple machine learning models using evaluation metrics and visualizations, including accuracy comparisons, AUC comparison charts, ROC curves, and confusion matrices.

According to the project report, **K-Nearest Neighbors (KNN), Neural Network, and Decision Tree** demonstrated better performance compared to the other evaluated models. KNN was highlighted for its predictive accuracy on the test set, while Logistic Regression showed the weakest accuracy among the compared models.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Machine Learning
- Data Visualization

## 🚀 Key Learnings

- Understanding and implementing a complete machine learning pipeline.
- Performing exploratory data analysis on healthcare-related data.
- Preprocessing datasets with missing values and categorical variables.
- Implementing supervised classification and unsupervised clustering algorithms.
- Evaluating and comparing models using multiple performance metrics.
- Understanding the challenges of class imbalance and model selection.

## ⚠️ Disclaimer

This project is intended for educational and research purposes only. The predictions are not a substitute for professional medical advice, clinical testing, or diagnosis.

## 👥 Contributors

- Mahajabin Chowdhury
- Alif Ahmed

## 📚 Project Information

- **Course:** CSE422 – Artificial Intelligence
- **Project Type:** Machine Learning Lab Project
