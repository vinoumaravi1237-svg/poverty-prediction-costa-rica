# Poverty Level Prediction – Costa Rican Household Data

# Machine Learning Project | MSc Economics & Analytics

# Project Overview

This project predicts the **poverty level** of households in Costa Rica using **Machine Learning** models.
The goal is to classify each family into one of four categories:

| Target Value | Poverty Level    |
| ------------ | ---------------- |
| 1            | Extreme Poverty  |
| 2            | Moderate Poverty |
| 3            | Vulnerable       |
| 4            | Non-Poor         |

The model helps government agencies and NGOs identify **who needs support the most** — enabling better welfare policy design.

# Dataset

* Source: Kaggle – Costa Rican Household Poverty Prediction
* Link: [https://www.kaggle.com/competitions/costa-rican-household-poverty-prediction](https://www.kaggle.com/competitions/costa-rican-household-poverty-prediction)
* 10,307 households | 172 features
* Includes:

  * Demographics
  * Housing conditions
  * Education levels
  * Asset ownership
  * Income and social indicators

---

# Tools and Libraries Used

| Technology             | Purpose                      |
| ---------------------- | ---------------------------- |
| Python 3.12            | Core language                |
| pandas, NumPy          | Data cleaning & manipulation |
| Matplotlib, Seaborn    | Data visualization           |
| Scikit-learn (sklearn) | ML models & evaluation       |
| Jupyter Notebook       | Development environment      |

---

# Methodology / Workflow

1. Data loading and structure analysis
2. Data cleaning

   * Handling missing values (median imputation)
   * Removing unwanted columns (`Id`, `idhogar`)
3. Exploratory Data Analysis

   * Education vs Poverty
   * Housing quality vs Poverty
   * Target distribution analysis
4. Train-test split (80-20)
5. Model training and prediction

   * Logistic Regression
   * Random Forest Classifier
6. Performance evaluation

   * Accuracy
   * Classification Report
   * Confusion Matrix
7. Feature Importance – Insights on poverty indicators

# Results

| Model               | Accuracy  | Key Observation                     |
| ------------------- | --------- | ----------------------------------- |
| Logistic Regression | 90.1%     | Struggles with minority classes     |
| Random Forest       | **90.5%** | Better at learning complex patterns |

**Education & Age** features were found to be the **most influential** factors affecting poverty.

# Key Insights

* Machine Learning can **automatically classify poverty** with high accuracy
* Education is the **strongest driver** of economic upliftment
* Data imbalance affects prediction of extreme-poor classes
* Potential use in **targeted welfare decisions**

# Future Improvements

* Class balancing (SMOTE or Class Weights)
* Try boosting models (XGBoost, LightGBM)
* Add regional economic indicators
* Deploy as a web-based poverty risk assessment tool

# Author

**Vinodhini R**
MSc Economics and Analytics
Christ (Deemed to be University), Delhi NCR

