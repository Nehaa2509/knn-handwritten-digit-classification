# Handwritten Digit Classification using KNN

## 📌 Project Overview
This project implements **Handwritten Digit Classification** using the
**K-Nearest Neighbors (KNN)** algorithm. The model is trained on the
**Sklearn Digits dataset**, where each digit image is represented as
numerical pixel values.

The goal is to understand **distance-based classification**, the impact
of feature scaling, and how to choose an optimal value of K.

---

## 🛠 Tools & Technologies
- Python
- Scikit-learn
- NumPy
- Matplotlib

---

## 📂 Dataset
- **Primary Dataset:** Sklearn Digits (`load_digits()`)
- Total samples: 1797
- Image size: 8 × 8 pixels
- Feature columns: 64 (flattened pixel values)
- Target labels: Digits from 0 to 9

Each row represents one handwritten digit image.

---

## ⚙️ Machine Learning Workflow
1. Loaded digits dataset and verified feature and label shapes  
2. Visualized sample digit images to confirm labels  
3. Split dataset into training and testing sets  
4. Applied **StandardScaler** since KNN is distance-based  
5. Trained KNN model with **K = 3**  
6. Evaluated accuracy on test data  
7. Tested multiple K values (3, 5, 7, 9)  
8. Plotted **Accuracy vs K** graph  
9. Generated **Confusion Matrix**  
10. Displayed test images with predicted labels  

---

## 📊 Evaluation
- **Metric Used:** Accuracy
- Accuracy improves or degrades depending on the value of K
- Optimal K is chosen based on Accuracy vs K plot

---

## 📈 Visual Outputs
- Accuracy vs K graph
- Confusion matrix
- Digit prediction visualization

---

## 🧠 Key Learnings
- KNN classifies data based on distance, not training
- Feature scaling is critical for distance-based models
- Low K causes overfitting, high K causes underfitting
- KNN is simple but computationally expensive on large datasets

---

## 📌 Interview Concepts Covered
- What is K in KNN
- Why scaling is required
- Euclidean distance
- Overfitting vs underfitting
- Limitations of KNN

---

## 📂 Project Structure
