# PCA – Dimensionality Reduction

## 📌 Task Description
This project demonstrates the use of Principal Component Analysis (PCA) to reduce the dimensionality of a dataset while preserving maximum variance.  
The reduced dataset is then used to train a Logistic Regression model and compare accuracy with the original dataset.

## 📊 Dataset Used
- Sklearn Digits Dataset (handwritten digits)

## 🛠 Tools & Libraries
- Python  
- Scikit-learn  
- Matplotlib  
- NumPy  

## ✅ Steps Performed
1. Loaded the digits dataset and flattened images into feature vectors  
2. Scaled features using StandardScaler  
3. Applied PCA with components: 2, 10, 30, 50  
4. Calculated explained variance ratio  
5. Plotted cumulative explained variance  
6. Reduced dataset using PCA  
7. Trained Logistic Regression on original dataset  
8. Trained Logistic Regression on reduced dataset  
9. Compared accuracy results  
10. Visualized PCA 2D scatter plot  

## 📈 Results
- PCA successfully reduced dimensions  
- Model accuracy remained high even after reduction  
- 2D PCA visualization showed class separation  

## 📂 Files Included
- `pca_digits.py` (Main Python code)  
- `README.md`  

## 🎯 Conclusion
PCA helps in reducing dataset size while retaining important features.  
It improves computational efficiency with minimal impact on accuracy.
