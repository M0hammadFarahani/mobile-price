# 📱 Mobile Price Classification - Machine Learning Project

This project is a **classification task** aimed at predicting the **price category** of a mobile phone based on its specifications using various machine learning algorithms.  

The dataset is clean, balanced, and contains various features such as battery power, RAM, screen size, and more.  



## 📂 Dataset

The dataset used is from [Kaggle - Mobile Price Classification](https://www.kaggle.com/iabhishekofficial/mobile-price-classification).  
It includes **2000 samples** with **20 numerical features**, and the target is a **price range** from 0 (lowest) to 3 (highest).



## 🚀 Project Workflow

1. **Data Preprocessing**
   - Feature inspection and EDA
   - Checked distributions and correlations
   - Feature scaling using `StandardScaler`

2. **Model Training**
   - Trained multiple models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest

3. **Hyperparameter Tuning**
   - Used GridSearchCV to tune Logistic Regression (but accuracy dropped)

4. **Final Model**
   - Best performance achieved by **Logistic Regression** with **97% accuracy**
   - GridSearch tuning result: 88%, so default configuration was used

---

## ✅ Result

- Final model: `LogisticRegression()`
- Accuracy: **97%**
- No further feature engineering was needed
- Project completed using **pure Scikit-learn**
