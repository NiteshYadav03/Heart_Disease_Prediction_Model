# Heart Disease Prediction

## Overview
The Heart Disease Prediction project is a machine learning application aimed at predicting whether an individual is at risk of developing heart disease in the future. Using historical health data, this system assists in early diagnosis and preventive healthcare.

This project leverages various machine learning techniques to analyze a dataset containing 14 features, including age, sex, chest pain type, cholesterol levels, and more. The final output is a binary classification where 1 indicates the presence of heart disease and 0 indicates its absence.

## Comprehensive Data Analysis
* Null values handling
* Categorical data encoding
* Outlier detection and removal
* Feature selection using correlation matrix
* Data scaling

## Technologies Used
* Programming Language: Python
* Libraries Used:
  * Scikit-learn: For implementing machine learning models.
  * NumPy: For numerical computations.
  * Pandas: For data manipulation and analysis.
  * Seaborn: For visualizing data distributions.
  * Matplotlib: For creating static, interactive, and animated visualizations.

## Dataset
* age: The person's age in years.

* sex: Whether the person is male (1) or female (0).

* cp (chest pain type): The kind of chest pain the person feels.
    * 0 = Typical chest pain caused by heart (angina).
    * 1 = Unusual chest pain.
    * 2 = Chest pain not related to the heart.
    * 3 = No chest pain, but has other symptoms (asymptomatic).

* trestbps (resting blood pressure): Blood pressure when the person is sitting still, measured in mm Hg.

* chol (cholesterol): The level of cholesterol (fat in the blood), measured in mg/dL. High cholesterol can be bad for the heart.

* fbs (fasting blood sugar): If the person's blood sugar is over 120 mg/dL after fasting (not eating) for some time.
    * 1 = Yes (high sugar)
    * 0 = No (normal sugar)

* restecg (resting ECG results): Result of a heart test (ECG) taken when the person is resting.
    * 0 = Normal
    * 1 = Some small problems with heartbeat
    * 2 = Serious heart-related changes

* thalach (maximum heart rate): The highest heart rate the person reached during exercise.

* exang (exercise-induced angina): Whether the person had chest pain during exercise.
    * 1 = Yes (had chest pain)
    * 0 = No (no chest pain)

* oldpeak: A number that shows how much the heart's performance dropped during exercise compared to rest. Higher numbers can mean more risk.

* slope: The shape of the curve made by the heart's performance during a test.
    * 0 = Going up (good)
    * 1 = Flat (not good)
    * 2 = Going down (bad)

* ca: Number of main heart blood vessels seen clearly in a special test. More blocked vessels can mean higher heart risk.

* thal: A blood disorder related to oxygen flow in the blood.
    * 1 = Normal
    * 2 = Fixed defect (a permanent problem)
    * 3 = Reversible defect (a temporary or fixable problem)

* target: This tells if the person has heart disease or not.
    * 1 = Person has heart disease
    * 0 = Person does NOT have heart disease

