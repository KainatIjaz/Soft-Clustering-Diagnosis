# 🏥 Soft Clustering for Enhancing the Diagnosis of Chronic Diseases  

## 📌 Overview  
This project explores the **Rough K-Means (RKM) clustering algorithm** to improve the classification of chronic diseases (Diabetes, Breast Cancer, and Kidney Disease).  
Comparisons are made with **K-Means, Gaussian Mixture Models (GMM), and Deep Neural Networks (DNN)** to evaluate diagnostic accuracy.  

## 📂 Dataset  
📌 **Data Sources:**  
- **Diabetes Dataset** (UCI Machine Learning Repository)  
- **Breast Cancer Dataset** (Kaggle)  
- **Chronic Kidney Disease Dataset** (Kaggle)  

## 🛠 Tools & Technologies  
🔹 Python | Scikit-learn | Pandas | NumPy | Machine Learning | Clustering | Deep Learning  

## 🔍 Methodology  
✔ **Data Preprocessing** (Handling missing values, standardization, feature selection)  
✔ **Clustering Algorithms**  
   - **Rough K-Means (RKM)** – Handles ambiguous data points  
   - **K-Means** – Traditional clustering method  
   - **Gaussian Mixture Models (GMM)** – Soft clustering approach  
✔ **Deep Neural Networks (DNN)** for improving classification accuracy  

## 📈 Results & Insights  
| Method | Accuracy | Precision (0) | Recall (0) | F1-Score (0) | Precision (1) | Recall (1) | F1-Score (1) |
|--------|----------|--------------|------------|--------------|--------------|------------|--------------|
| **Rough K-Means** | 0.68 | 0.83 | 0.64 | 0.72 | 0.53 | 0.75 | 0.62 |
| **Traditional K-Means** | 0.32 | 0.47 | 0.32 | 0.38 | 0.20 | 0.31 | 0.24 |
| **Gaussian Mixture** | 0.34 | 1.00 | 1.00 | 1.00 | 0.00 | 0.00 | 0.00 |
| **Deep Neural Network (DNN)** | **0.89** | **0.98** | **0.81** | **0.89** | **0.82** | **0.98** | **0.89** |

✔ **Deep Neural Networks outperformed all clustering methods, achieving 89% accuracy.**  
✔ **Rough K-Means significantly improved classification over traditional K-Means and GMM.**  

## 🚀 How to Run  
1️⃣ **Install dependencies:**  
   ```bash
   pip install pandas scikit-learn numpy tensorflow
