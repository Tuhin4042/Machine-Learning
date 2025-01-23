## What is Naïve Bayes?  

Naïve Bayes is a supervised machine learning algorithm based on Bayes' Theorem, assuming strong (naïve) independence between features. Despite its simplicity, Naïve Bayes performs well in many real-world applications, especially for text classification and spam detection.  

---

## Why Use Naïve Bayes?  

Naïve Bayes is widely used due to its simplicity and speed.  

- **Applications**:  
  - Spam detection (e.g., classifying emails as spam or not spam).  
  - Sentiment analysis (e.g., positive vs. negative reviews).  
  - Document classification (e.g., topic modeling).  
  - Medical diagnosis (e.g., predicting diseases based on symptoms).  

- **Advantages**:  
  - Fast to train and predict.  
  - Handles large datasets efficiently.  
  - Performs well with high-dimensional data (e.g., text data).  

- **Limitations**:  
  - Assumes feature independence, which may not hold in all datasets.  
  - Struggles with datasets where features are highly correlated.  
  - Requires non-zero probabilities; smoothing techniques are often applied.  

---

## Types of Naïve Bayes Classifiers  

1. **Gaussian Naïve Bayes**: Assumes continuous features follow a normal (Gaussian) distribution.  
2. **Multinomial Naïve Bayes**: Suitable for discrete data (e.g., text classification with word counts).  
3. **Bernoulli Naïve Bayes**: Used for binary/boolean features (e.g., presence/absence of words).  

---

## Features  

- Implementation of Gaussian, Multinomial, and Bernoulli Naïve Bayes classifiers.  
- Data preprocessing, including text vectorization (e.g., TF-IDF, CountVectorizer) for text-based datasets.  
- Evaluation metrics such as Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.  
- Example use cases for spam detection and sentiment analysis.  

---

## Prerequisites  

To run this project, ensure you have the following:  
- Python 3.8 or higher.  
- Required libraries:  
  - `numpy`  
  - `pandas`  
  - `scikit-learn`  
  - `matplotlib`  
  - `seaborn`  

Install dependencies with:  
```bash
pip install -r requirements.txt

