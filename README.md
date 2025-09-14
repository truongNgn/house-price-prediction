# 🏠 Housing Price Prediction

This project explores and predicts housing prices using machine learning techniques.  
It includes **exploratory data analysis (EDA)**, **feature engineering**, **dimensionality reduction (PCA)**, and **model comparison** to build robust regression models for real estate pricing.

---

## 📂 Project Structure

- `housingprice-data.ipynb`  
  Data exploration and preprocessing (EDA, feature analysis, feature scaling, encoding).

- `housingprice-model-no-pca.ipynb`  
  Baseline regression models without PCA.

- `housingprice-model-pca.ipynb`  
  Regression models with PCA for dimensionality reduction and performance comparison.

---

## 🚀 Workflow

1. **Data Analysis**  
   - Checked missing values, distributions, outliers, and correlations between housing features.  
   - Visualized feature relationships using heatmaps and scatter plots.

2. **Preprocessing**  
   - Feature scaling and encoding of categorical attributes.  
   - Outlier detection and cleaning.  
   - PCA applied in a separate pipeline to reduce dimensionality.

3. **Modeling**  
   - Trained and compared multiple regression models:  
     - Linear Regression  
     - Random Forest Regressor  
     - Gradient Boosting Regressor  
   - Compared performance with and without PCA.

4. **Evaluation**  
   - Metrics: Mean Squared Error (MSE), R² Score.  
   - Visualizations of prediction accuracy and error distribution.

---

## 📊 Results

- PCA improved training efficiency while preserving accuracy.  
- Gradient Boosting and Random Forest provided the most robust predictions.  
- Achieved competitive **R² and MSE scores** across experiments.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Jupyter Notebook  
- Machine Learning: Regression, PCA, Model Evaluation  

---

## 🎯 Key Takeaways

- Demonstrated complete ML workflow from **EDA → Preprocessing → Modeling → Evaluation**.  
- Compared dimensionality reduction impact (PCA vs. non-PCA).  
- Provided interpretable insights for housing market pricing.

---

