# Titanic-Survival-Prediction

A Machine Learning project that predicts passenger survival on the Titanic dataset using **Logistic Regression** and exploratory data analysis techniques.

## Project Overview

This project focuses on analyzing the Titanic dataset, cleaning and preprocessing the data, engineering useful features, and building a classification model to predict passenger survival.

The main objective was not only achieving good accuracy, but also understanding the complete Machine Learning workflow from data exploration to model evaluation.

---

## Dataset

The dataset contains information about Titanic passengers such as:

* Age
* Gender
* Passenger Class
* Fare
* Family Members
* Embarked Location
* Survival Status

Target Variable:

* `Survived`

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Data Exploration (EDA)

* Analyzed missing values
* Explored feature distributions
* Visualized survival patterns
* Studied correlations between features and survival

### 2. Data Preprocessing

* Handled missing values
* Removed unnecessary columns
* Encoded categorical variables
* Scaled numerical features

### 3. Feature Engineering

Created new features such as:

* `FamilySize`
* `IsAlone`
* `Title` extracted from passenger names

### 4. Model Building

Implemented:

* Logistic Regression

### 5. Model Evaluation

Evaluated the model using:

* Accuracy Score
* Classification Report
* Confusion Matrix
* ROC Curve
* ROC-AUC Score

---

## Results

* **Test Accuracy:** ~77%
* **ROC-AUC Score:** ~0.83

The model achieved stable and reasonable performance considering the relatively small dataset size.

---

## Key Insights

* Female passengers had a significantly higher survival rate than males.
* Higher ticket fares were associated with higher survival probability.
* Third-class passengers had the lowest survival rate.
* Family-related features improved prediction performance.
* The dataset was relatively small, which limited achieving higher accuracy.

---

## Visualizations Included

* Survival Distribution
* Age Distribution
* Fare Distribution
* Correlation Heatmap
* ROC Curve
* Confusion Matrix

---

## Future Improvements

* Try additional classification models
* Apply Hyperparameter Tuning
* Use Pipelines for cleaner preprocessing
* Perform Cross Validation
* Deploy the model as a web application

---

## Repository Structure

```bash
├── Titanic_task.ipynb
├── README.md
└── dataset/
```

---

## Author

Viola Ibrahim

Machine Learning & Software Development Enthusiast
