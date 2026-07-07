# Fake Account Detection Using Support Vector Machine (SVM)

## 📌 Project Overview

This project focuses on detecting fake and genuine social media accounts using the **Support Vector Machine (SVM)** machine learning algorithm.

The model analyzes user profile features and classifies accounts into two categories:
- ✅ Genuine Account
- ❌ Fake Account

The project includes data preprocessing, exploratory data analysis (EDA), feature scaling, SVM model training, prediction, and performance evaluation.

---

## 🎯 Objective

The main objective of this project is to build a machine learning model that can automatically identify fake accounts based on account characteristics and improve detection accuracy.

---

## 📂 Dataset

**Dataset Name:** Instagram Fake Spammer Genuine Accounts Dataset

**Source:** Kaggle

Dataset Link:
https://www.kaggle.com/datasets/free4ever1/instagram-fake-spammer-genuine-accounts

### Features Used:
- Profile picture availability
- Username characteristics
- Full name details
- Description length
- External URL information
- Account privacy status
- Number of posts
- Number of followers
- Number of following

### Target Variable:
- `fake`
  - 0 → Genuine Account
  - 1 → Fake Account

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🔍 Project Workflow

## 1. Data Collection
- Load the Instagram account dataset.
- Understand dataset structure and features.

## 2. Data Preprocessing
- Check missing values.
- Remove unnecessary data.
- Prepare features and target variables.

## 3. Exploratory Data Analysis (EDA)
Performed visual analysis using:
- Fake vs Genuine account distribution
- Followers distribution
- Following distribution
- Correlation heatmap

## 4. Feature Scaling

StandardScaler is applied to normalize feature values.

Formula:

\[
z = \frac{x-\mu}{\sigma}
\]

Feature scaling is important because SVM depends on distance calculations.

---

# 🤖 Machine Learning Model

## Support Vector Machine (SVM)

SVM is a supervised machine learning algorithm used for classification.

It finds the best hyperplane that separates different classes with maximum margin.

### Hyperplane Equation:

\[
w.x+b=0
\]

Where:
- w = weight vector
- x = input features
- b = bias term

---

# 🏗️ Model Implementation

Steps:
1. Split data into training and testing sets.
2. Apply feature scaling.
3. Train SVM classifier.
4. Predict results.
5. Evaluate model performance.

---

# 📊 Model Evaluation

The model is evaluated using:

### Accuracy Score
Measures overall correctness of predictions.

### Classification Report
Includes:
- Precision
- Recall
- F1-score

### Confusion Matrix
Shows:
- True Positive
- True Negative
- False Positive
- False Negative

---

# 📈 Results

- SVM successfully classified fake and genuine accounts.
- The model achieved good classification accuracy.
- The confusion matrix shows the performance of predictions.
- Feature scaling improved model efficiency.

---

# 📁 Project Structure
