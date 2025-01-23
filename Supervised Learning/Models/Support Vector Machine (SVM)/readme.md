## What is SVM?  

Support Vector Machine (SVM) is a supervised machine learning algorithm that finds a hyperplane in an N-dimensional space (N being the number of features) that distinctly separates data points into different classes. SVM is highly effective for both linear and non-linear classification problems, especially in high-dimensional spaces.  

Key Concept:  
- SVM maximizes the margin (distance) between the hyperplane and the nearest data points of any class, known as **support vectors**.  

---

## Why Use SVM?  

SVM is widely used due to its robustness and versatility:  

- **Applications**:  
  - Text categorization (e.g., spam detection).  
  - Image recognition (e.g., handwritten digit classification).  
  - Bioinformatics (e.g., gene classification).  
  - Sentiment analysis.  

- **Advantages**:  
  - Works well for high-dimensional datasets.  
  - Effective when the number of features is greater than the number of samples.  
  - Supports both linear and non-linear classification using kernel tricks.  
  - Robust to overfitting, especially in high-dimensional spaces.  

- **Limitations**:  
  - Not suitable for very large datasets due to high computational cost.  
  - Performance is sensitive to the choice of kernel and hyperparameters.  

---

## How Does SVM Work?  

1. **Linear SVM**:  
   - Finds a straight-line hyperplane to separate data into two classes.  

2. **Non-Linear SVM**:  
   - Maps data into higher-dimensional space using kernels (e.g., polynomial, RBF) to find a hyperplane for separation.  

3. **Kernels**:  
   - Linear Kernel  
   - Polynomial Kernel  
   - Radial Basis Function (RBF) Kernel  
   - Sigmoid Kernel  

---

## Features  

- Implementation of SVM for classification tasks.  
- Support for linear and non-linear classification using different kernels.  
- Data preprocessing, feature scaling, and hyperparameter tuning.  
- Evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and ROC-AUC.  
- Visualization of decision boundaries for 2D datasets.  

---

## Prerequisites  

To run this project, ensure you have the following installed:  
- Python 3.8 or higher.  
- Required libraries:  
  - `numpy`  
  - `pandas`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  
