# Heart Disease Predictor

## Overview:

This project implements a heart disease predictor using a Random Forest Classifier to predict the likelihood of heart disease based on various health and lifestyle parameters.

## Dataset:
The dataset used (`heart_disease.csv`) contains the following columns:

- **Age**: Age of the patient
- **Sex**: Gender of the patient (1 = male, 0 = female)
- **CP**: Chest pain type (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic)
- **Trestbps**: Resting blood pressure (in mm Hg)
- **Chol**: Serum cholesterol (in mg/dl)
- **Fbs**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **Restecg**: Resting electrocardiographic results (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy)
- **Thalach**: Maximum heart rate achieved
- **Exang**: Exercise induced angina (1 = yes, 0 = no)
- **Oldpeak**: ST depression induced by exercise relative to rest
- **Slope**: The slope of the peak exercise ST segment (1 = upsloping, 2 = flat, 3 = downsloping)
- **Ca**: Number of major vessels (0-3) colored by fluoroscopy
- **Thal**: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)
- **Target**: Presence of heart disease (1 = presence, 0 = absence)

## Libraries Used:
- **numpy** (version 1.26.4): For numerical computations and array operations.
- **pandas** (version 2.1.4): For data manipulation and analysis.
- **matplotlib** (version 3.4.2): For creating visualizations of the data.
- **seaborn** (version 0.12.2): For statistical data visualization.
- **sklearn**(version 1.2.2): For loading and processing data
