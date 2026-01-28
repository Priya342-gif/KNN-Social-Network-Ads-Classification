# KNN Social Network Ads Classification

## 📌 Project Overview
This project demonstrates the implementation of the **K-Nearest Neighbors (KNN)** algorithm for a **binary classification** problem using the **Social Network Ads dataset**.

The model predicts whether a user will **purchase a product or not** based on:
- Age
- Estimated Salary

---

## 🧠 Algorithm Used: K-Nearest Neighbors (KNN)

KNN is a **supervised machine learning algorithm** that classifies a data point based on the majority class of its **K nearest neighbors** using distance metrics.

---

## 📂 Dataset Information
- Dataset Name: **Social_Network_Ads.csv**
- Features:
  - Age
  - Estimated Salary
- Target:
  - Purchased (0 = No, 1 = Yes)

---

## ⚙️ Steps Performed
1. Import required libraries (NumPy, Pandas, Matplotlib)
2. Load the dataset
3. Split data into training and test sets
4. Apply **Feature Scaling** using StandardScaler
5. Train the KNN classifier
6. Predict test results
7. Evaluate the model using:
   - Confusion Matrix
   - Accuracy Score
8. Visualize the decision boundary

---

## 🛠️ Model Parameters
- Number of Neighbors (K): **5**
- Distance Metric: **Euclidean Distance**
- Library Used: **scikit-learn**

---

## 📊 Results
- The model successfully classifies users into purchasing and non-purchasing categories.
- Accuracy is evaluated using the confusion matrix and accuracy score.

---

## 🖥️ Visualization
The project includes a 2D visualization showing:
- Decision regions
- Classified data points
- Clear separation between classes

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Priya342-gif/KNN-Social-Network-Ads-Classification.git
