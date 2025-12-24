# 🌦️ Weather Classification using K-Nearest Neighbors (KNN)

This repository contains a **Weather Classification system** built using the  
**K-Nearest Neighbors (KNN)** machine learning algorithm.

The project focuses not only on achieving good accuracy but also on understanding  
how a **distance-based algorithm** works internally.

---

## 🚀 Project Overview

Weather classification plays an important role in areas such as:
- Agriculture 🌾
- Aviation ✈️
- Daily planning 📅

In this project, a **KNN classifier** is used to predict weather categories based on  
numerical and categorical weather features.

### 🎯 Key Objectives

- Understanding the working principle of KNN  
- Studying the effect of feature scaling  
- Analyzing the impact of different **k** values  
- Evaluating model performance using multiple metrics  

---

## 🧠 Algorithm Used

### 🔹 K-Nearest Neighbors (KNN)

- **Type:** Supervised Learning (Classification)

**Concept:**  
A data point is classified based on the majority class of its **k nearest neighbors**,  
determined using distance metrics (**Euclidean distance** by default).

### Important Characteristics of KNN

- No explicit training phase (lazy learning)  
- Distance-based decision making  
- Highly sensitive to feature scaling  
- Performance depends on the choice of **k**

---

## 📂 Project Workflow

### 1️⃣ Import Libraries
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  

### 2️⃣ Load Dataset
- Read the weather dataset  
- Inspect features and target variable  

### 3️⃣ Data Preprocessing
- Encode target labels  
- One-Hot Encoding for categorical features  
- Feature scaling using **StandardScaler**

### 4️⃣ Train–Test Split
- Split data into training and testing sets  

### 5️⃣ Model Building
- Implement KNN classifier  
- Experiment with different values of **k**

### 6️⃣ Model Evaluation
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)

---

## 📊 Model Evaluation Metrics

The model performance is evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

These metrics provide both **overall performance** and **class-wise insights**.

---

## ⚙️ Why Feature Scaling is Important in KNN

KNN relies on **distance calculations**.  
If features are on different scales, variables with larger magnitudes dominate the  
distance computation.

### ✔ Feature scaling ensures:
- Fair distance measurement  
- Improved model performance  
- Stable and meaningful neighbor selection  

For this reason, **StandardScaler** is applied before training the KNN model.

---

## 🧪 Experimentation & Observations

- Tested multiple values of **k**  
- Observed the **bias–variance tradeoff**  
- Compared model performance before and after scaling  
- Found that proper preprocessing significantly improves accuracy  

---

## 📁 Repository Structure

```text
├── Weather_task_knn.ipynb
├── weather_classification_data.csv
├── README.md
├── requirements.txt


---

👨‍💻 Author

Bijili Pavan
🎓 B.Tech – Computer Science (AI & ML)
📊 Machine Learning & Data Science Enthusiast
