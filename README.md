# Heart-Disease-Prediction-Using-Machine-Learning
# Problem Statement
Heart disease is one of the leading causes of death worldwide. Early detection can help in better treatment and prevention.

Objective: Predict the likelihood of heart disease based on patient health data.

# 📊 Dataset Overview
- Source: [Kaggle - UCI Heart Disease Dataset ](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- Total Records: 303
- Features: 14 (Age, Sex, Cholesterol, Max Heart Rate, etc.)
- Target: 1 = Disease Present, 0 = No Disease
- Each record represents one patient.

## ⚙️ Data Preprocessing
- Loaded dataset using pandas.
- Checked for missing values and data consistency.
- Converted necessary columns to correct data types.
- Separated data into input features (X) and target label (y).

# Exploratory Data Analysis (EDA)
- Visualized age distribution and disease frequency.
- Compared cholesterol levels and heart disease.
- Generated correlation heatmap to find relationships.
- Found that older age, high cholesterol, and low heart rate are risk indicators.

# Model Building
- Split data into 80% training and 20% testing sets.
- Chose Logistic Regression as model (suitable for binary classification).
- Trained the model using sklearn.
- Predicted outcomes for test data.

# Results and Insights
Important predictive features:
   - Age
   - Chest Pain Type (cp)
   - Cholesterol (chol)
   - Max Heart Rate (thalach)
Logistic Regression provides easy interpretability. Useful for early screening and diagnosis support.

# Conclusion
- The project successfully predicted heart disease likelihood.
- Logistic Regression gave reliable and interpretable results.
- Can assist healthcare professionals in decision-making.
- Future Work: Try Decision Tree, Random Forest, or Deep Learning for better accuracy.


