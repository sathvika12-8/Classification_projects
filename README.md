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
# 🛒 Amazon Product Recommendation System using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project implements a **Product Recommendation System** using the **K-Nearest Neighbors (KNN)** machine learning algorithm. The system recommends products that are similar to a selected product based on features such as rating, price, discount, and reviews.

The project demonstrates the complete machine learning workflow, including data preprocessing, feature scaling, model building, and recommendation generation.

---

## 🎯 Objective

The objective of this project is to build a recommendation system that helps users discover similar products by analyzing product features and measuring similarity using the KNN algorithm.

---

## 📂 Dataset

**Dataset Name:** Amazon Products Dataset

**Source:** Kaggle

**Dataset Link:**
https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset

### Features Used
- Product Name
- Rating
- Number of Reviews
- Discount Price
- Actual Price
- Discount Percentage

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

# 🔄 Project Workflow

```
Load Dataset
      ↓
Data Cleaning
      ↓
Feature Selection
      ↓
Feature Scaling
      ↓
Build KNN Model
      ↓
Train Model
      ↓
Find Nearest Products
      ↓
Recommend Similar Products
```

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset information
- Missing value analysis
- Product rating distribution
- Price distribution
- Correlation heatmap

---

## ⚙️ Data Preprocessing

- Removed missing values
- Converted price columns into numeric format
- Selected useful numerical features
- Standardized features using **StandardScaler**

---

## 🤖 Machine Learning Algorithm

### K-Nearest Neighbors (KNN)

KNN is a supervised machine learning algorithm that predicts similar items by finding the nearest neighbors based on distance.

### Distance Formula

Euclidean Distance

\[
d=\sqrt{\sum (x_i-y_i)^2}
\]

Where:

- **d** = Distance
- **x** = Selected product
- **y** = Other products

Smaller distance indicates greater similarity.

---

## 📈 Model Implementation

1. Import libraries
2. Load dataset
3. Clean data
4. Select features
5. Apply feature scaling
6. Build KNN model
7. Train model
8. Recommend similar products

---

## 📊 Results

- Successfully built a product recommendation system.
- Recommended similar products based on feature similarity.
- Feature scaling improved recommendation quality.
- KNN effectively identified the nearest products using Euclidean distance.

---

## 📁 Project Structure

```
Amazon-Product-Recommendation-KNN/
│
├── dataset/
│   └── amazon.csv
│
├── images/
│   ├── rating_distribution.png
│   ├── price_distribution.png
│   ├── heatmap.png
│   └── workflow.png
│
├── Amazon_KNN.ipynb
├── Amazon_KNN.py
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/Amazon-Product-Recommendation-KNN.git
```

### Install Required Libraries

```bash
pip install -r requirements.txt
```

### Run the Project

Open the notebook:

```
Amazon_KNN.ipynb
```

Run all cells to generate recommendations.

---

## 📊 Evaluation

The recommendation system identifies products that are most similar to the selected product using Euclidean distance and nearest-neighbor search.

---

## 💡 Applications

- E-commerce product recommendation
- Online shopping platforms
- Personalized product suggestions
- Customer shopping assistance

---

## 🚀 Future Enhancements

- Implement user-based collaborative filtering.
- Add content-based recommendations using product descriptions.
- Deploy the project using Streamlit or Flask.
- Improve recommendations using hybrid recommendation techniques.

---

## 👨‍💻 Author

**Your Name**

Machine Learning | Python | Data Science

If you found this project useful, feel free to ⭐ this repository.
