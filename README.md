# Heart-Disease-prediction
This repository contains a dataset focused on heart disease. The goal of this project is to predict the presence of heart disease in patients based on various medical attributes.

## Dataset Description

The heart disease dataset includes a variety of features that are commonly associated with cardiovascular health. Each row in the dataset represents a patient, while the columns provide information such as:

- **Age**: The age of the patient.
- **Sex**: Gender of the patient (1 = male, 0 = female).
- **Chest Pain Type**: Type of chest pain experienced.
- **Resting Blood Pressure**: Blood pressure measured at rest.
- **Cholesterol**: Serum cholesterol in mg/dl.
- **Fasting Blood Sugar**: Fasting blood sugar level (> 120 mg/dl = 1, else = 0).
- **Resting ECG Results**: Results of resting electrocardiographic tests.
- **Maximum Heart Rate Achieved**: Maximum heart rate during exercise.
- **Exercise Induced Angina**: Angina induced by exercise (1 = yes, 0 = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope of Peak Exercise ST Segment**: Slope of the peak exercise ST segment.
- **Number of Major Vessels**: Number of major vessels (0-3) colored by fluoroscopy.
- **Thalassemia**: Thalassemia status (1 = normal; 2 = fixed defect; 3 = reversable defect).
- **Target**: Diagnosis of heart disease (1 = presence, 0 = absence).

## Algorithm Justification

For this project, Logistic Regression was chosen as the machine learning algorithm due to its effectiveness in binary classification tasks, particularly in medical datasets where the outcome is often categorical (presence or absence of disease). 

### Why Logistic Regression?

1. **Interpretability**: Logistic Regression provides coefficients that can be easily interpreted, allowing us to understand the impact of each feature on the likelihood of heart disease.
  
2. **Efficiency**: It is computationally efficient and works well with smaller datasets, making it suitable for this project.

3. **Performance**: The model achieved an accuracy of approximately **90.74%**, indicating that it correctly predicts the presence or absence of heart disease in about 90.74% of cases. This high accuracy suggests that the model is effective and reliable for this dataset.

4. **Probabilistic Output**: Logistic Regression outputs probabilities, which can be useful for risk assessment in clinical settings.

## Results

The Logistic Regression model achieved an accuracy of **0.9074** on the test dataset. This performance metric indicates a strong predictive capability, making it a valuable tool for assessing heart disease risk.

## Conclusion

This project demonstrates the application of Logistic Regression to predict heart disease using a well-structured dataset. The high accuracy achieved suggests that this model can be a useful aid in clinical decision-making and patient assessment.

## Future Work

Future improvements could include:

- Exploring other algorithms (e.g., Random Forest, Support Vector Machines) to compare performance.
- Conducting feature engineering to enhance model accuracy.
- Implementing cross-validation techniques for more robust evaluation.



Thank you for your interest in this project. Your feedback and contributions are welcome!
