# 🌍 Life Expectancy Prediction with Machine Learning

This project aims to predict life expectancy using socio-economic, demographic, and health-related indicators through a complete end-to-end machine learning pipeline.

---

## 🚀 Project Workflow

### 🔹 1. Data Preprocessing
- Cleaned column names  
- Handled missing values  
- Removed multicollinearity via correlation analysis  
- Dropped redundant features  

### 🔹 2. Exploratory Data Analysis (EDA)
- Analyzed feature distributions  
- Detected skewed variables  
- Observed outliers and data spread  

### 🔹 3. Feature Engineering
- Applied **Yeo-Johnson power transformation** to reduce skewness  
- Encoded categorical features  
- Performed feature scaling  

### 🔹 4. Modeling
Multiple regression models were evaluated:

- Linear Regression  
- Random Forest
- Decision Tree
- Lasso
- Ridge
- Gradient Boosting  
- LightGBM  
- XGBoost  

### 🔹 5. Hyperparameter Tuning
- Used **RandomizedSearchCV** for efficient optimization  
- Focused on ensemble models to maximize performance  

---

## 📊 Results

| Model | R² Score |
|------|----------|
| **LightGBM (Tuned)** | **~0.96** |

The tuned LightGBM model achieved excellent generalization with minimal overfitting.

---

## 🔍 Key Findings

Life expectancy is strongly influenced by:

- Education level (schooling)  
- Income composition  
- GDP  
- Adult mortality  
- HIV/AIDS prevalence  

Ensemble-based models captured complex non-linear relationships more effectively than linear models.

---

## 🧠 Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- LightGBM  
- XGBoost  
- Matplotlib  

---

## 🎯 Conclusion

This project demonstrates that combining proper preprocessing, feature engineering, and advanced ensemble learning methods enables highly accurate modeling of life expectancy. The results highlight the importance of socio-economic and health-related factors in determining longevity.
