# Predicting Mental Distress Using BRFSS 2024

This project explores the use of statistical learning and machine learning techniques to predict mental health outcomes using the 2024 Behavioral Risk Factor Surveillance System (BRFSS) dataset from the CDC. The analysis focuses on identifying patterns associated with frequent mental distress and estimating the number of mentally unhealthy days reported by adults in the United States.

The project was completed as part of the course **STAT 5603: Statistical Learning and Data Mining** at Temple University.

---

## Project Objectives

The study investigates two primary prediction tasks:

- **Classification Task:** Predicting whether an individual experiences *frequent mental distress* (14 or more mentally unhealthy days in the past 30 days).
- **Regression Task:** Predicting the exact number of mentally unhealthy days reported within the past month.

The project also compares the performance of multiple statistical and machine learning models to determine which approaches are most effective for mental health screening and prediction.

---

## Dataset

The analysis uses the **2024 Behavioral Risk Factor Surveillance System (BRFSS)** dataset published by the Centers for Disease Control and Prevention (CDC).

- Total records analyzed: **457,670**
- Original variables: **301**
- Final cleaned predictors used: **27**

The selected variables include:
- Physical health indicators
- Depression diagnosis history
- Functional limitations
- Healthcare access barriers
- Demographic characteristics
- Lifestyle and behavioral factors

---

## Methods Used

### Classification Models
- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Quadratic Discriminant Analysis (QDA)
- Random Forest Classifier

### Regression Models
- Linear Regression
- Random Forest Regression

### Additional Techniques
- Principal Component Analysis (PCA)
- Cross-validation
- Feature importance analysis
- Precision-recall evaluation for imbalanced classification

---

## Key Findings

- **QDA** achieved the highest recall for detecting frequent mental distress, making it the strongest screening-oriented classification model.
- **Random Forest** achieved the best ROC AUC and average precision among classification models.
- **Random Forest Regression** outperformed linear regression for predicting mentally unhealthy days.
- The most influential predictors included:
  - Prior depression diagnosis
  - Cognitive difficulty
  - Physical health burden
  - Functional limitations
  - Healthcare affordability barriers

---

## Technologies & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Evaluation Metrics

### Classification
- Recall
- Precision
- F1 Score
- ROC AUC
- Average Precision

### Regression
- RMSE
- R-squared

---

## Project Significance

This project demonstrates how public health survey data can be used to identify mental health risk patterns at the population level. The findings highlight the strong relationship between mental distress, physical health, disability, and access to healthcare, while also showing the challenges of accurately modeling mental health outcomes using survey-based data.

---

## Authors

- Bharati Sahani
- Enestina Raradza
- Prince M. Nkomo
- Sheena Huang
- Steven Nguyen

---

## Academic Context

**Course:** STAT 5603 – Statistical Learning and Data Mining  
**Instructor:** Professor Peter Califano  
**Institution:** Temple University

---

## References

- CDC BRFSS Dataset: https://www.cdc.gov/brfss/index.html
- Scikit-learn Documentation: https://scikit-learn.org/stable/
