# Customer Churn Prediction

This project analyzes a telecom customer dataset and builds machine learning models to predict whether a customer will churn.  
It includes data cleaning, feature engineering, model training (Logistic Regression, KNN, SVM, Decision Tree), and a Streamlit app for interactive prediction.

---

## 📌 Project Overview

The workflow includes:

1. **Loading and cleaning the data**
2. **Encoding categorical variables**
3. **Feature engineering**
4. **Scaling numerical features**
5. **Training four ML models:**
   - Logistic Regression  
   - KNN Classifier  
   - SVM  
   - Decision Tree  
6. **Hyperparameter tuning using GridSearchCV**
7. **Evaluating the final models**
8. **Building a Streamlit app for predictions**


## 🚀 How to Run the Project

### **1. Install required libraries**

```
pip install -r requirements.txt
```

If you don’t have a requirements file:

```
pip install pandas numpy scikit-learn streamlit
```

---

### **2. Run the analysis (optional)**  
You can open the `analysis.ipynb` file in Jupyter Notebook or VS Code to view the full workflow.

---

## 🎛 Running the Streamlit App

To launch the app:

```
streamlit run app.py
```

Then open the local URL shown in your terminal 
---

## 📝 Features of the Streamlit App

- User inputs customer details  
- The app preprocesses the input the same way as the training pipeline  
- Loads the best trained model  
- Predicts whether the customer will churn  
- Displays the result clearly to the user  

