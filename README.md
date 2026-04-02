# Binary Classification Model for Diabetes Diagnosis

## Project Overview
This project aims to build a binary classification model to predict whether a patient has diabetes based on medical features. The analysis includes data exploration, model training, evaluation, and performance improvement.

---

## Dataset
The dataset contains medical predictor variables such as:
- Glucose
- Blood Pressure
- BMI
- Age
- Insulin level

The target variable indicates whether the patient has diabetes (1) or not (0).

---

## Methodology

### 1. Data Exploration
- Performed data quality checks
- Visualized key features to understand distributions and relationships

### 2. Baseline Model
- Logistic Regression was used as the baseline model
- Evaluated using accuracy, precision, recall, and F1 score

### 3. Feature Selection
- Removed less relevant features to reduce noise and improve model performance

### 4. Alternative Model
- Random Forest was applied to capture non-linear relationships

### 5. Hyperparameter Tuning
- GridSearchCV was used to optimize parameters:
  - n_estimators
  - max_depth
  - min_samples_split

---

## Results

| Model | Accuracy | Recall | F1 Score |
|------|--------|--------|---------|
| Logistic Regression | 0.77 | 0.54 | 0.62 |
| Random Forest (Tuned) | 0.79 | 0.63 | 0.68 |

The tuned Random Forest model improved recall and F1 score, making it more effective in identifying positive diabetes cases.

---

## Conclusion
The results show that model choice and hyperparameter tuning significantly improve performance. Random Forest outperformed Logistic Regression by capturing more complex patterns in the data.

---

## Tools and Technologies
- Python
- Scikit-learn
- Pandas
- Matplotlib

---

## GitHub Repository
This project is part of a data science assignment and demonstrates skills in:
- Model building
- Evaluation
- Hyperparameter tuning
- Version control using GitHub
