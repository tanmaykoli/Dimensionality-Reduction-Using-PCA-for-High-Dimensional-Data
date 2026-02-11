# 📊 Dimensionality Reduction Using PCA    

👤 **Name:** Tanmay Koli  
🎓 **Domain:** Data Science  

---

## 📌 Project Overview  

High-dimensional datasets often contain redundant and correlated features that increase computational complexity and may affect model performance.

This project demonstrates the use of **Principal Component Analysis (PCA)** to reduce dimensionality while preserving maximum variance. A Random Forest classifier is trained before and after applying PCA to compare performance.

---

## 🎯 Objectives  

- Understand high-dimensional data challenges  
- Apply feature scaling before PCA  
- Perform dimensionality reduction  
- Retain maximum data variance  
- Compare model performance before and after PCA  
- Visualize reduced feature space  

---

## 📂 Dataset Information  

- Dataset: **Wine Dataset (Scikit-learn Built-in)**
- Total Samples: 178  
- Original Features: 13  
- Target Classes: 3  

The dataset is loaded directly from `sklearn` to ensure reproducibility and smooth execution.

---

## 🛠 Tools & Technologies Used  

- Python  
- Jupyter Notebook  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ⚙️ Project Workflow  

1. Import required libraries  
2. Load dataset  
3. Perform exploratory data analysis (EDA)  
4. Feature scaling using StandardScaler  
5. Train baseline model (Random Forest)  
6. Apply PCA  
7. Analyze explained variance  
8. Reduce dimensionality to 8 principal components  
9. Train model after PCA  
10. Compare performance  

---

## 📊 Results  

- Original Features: 13  
- Reduced Features: 8  
- Variance Preserved: ~92–95%  
- Accuracy Before PCA: 1.0  
- Accuracy After PCA: 1.0  

PCA successfully reduced feature dimensionality without reducing classification accuracy.

---

## 📈 Key Insights  

- PCA removes multicollinearity  
- Reduces redundant information  
- Preserves most of the variance  
- Maintains predictive performance  
- Enables visualization of complex datasets in 2D  

---

## 🚀 Future Improvements  

- Implement Kernel PCA  
- Compare with feature selection techniques  
- Apply PCA on other high-dimensional datasets  
- Analyze computational time improvement  

---

## 📁 Project Structure  

```
Week7_Dimensionality_Reduction_PCA.ipynb
README.md
requirements.txt
```

---

## 🧠 Conclusion  

Dimensionality reduction using PCA effectively handled correlated high-dimensional data while preserving information and maintaining model accuracy. This demonstrates the importance of feature extraction techniques in real-world machine learning workflows.

