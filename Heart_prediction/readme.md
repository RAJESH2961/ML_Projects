# Heart Disease Prediction Using Machine Learning

This project aims to predict the likelihood of heart disease in individuals based on various health metrics using machine learning techniques. By leveraging supervised learning algorithms, the model helps identify potential heart disease cases for early intervention and medical support.

---

## Project Overview
Heart disease is a leading cause of mortality worldwide. Early detection can significantly improve management and outcomes. This project utilizes historical data, such as cholesterol levels, resting blood pressure, and maximum heart rate, to build a predictive model that identifies individuals at risk of developing heart disease.

---

## Features of the Dataset
The dataset includes the following features:

- **Age**: Age of the individual.
- **Sex**: Gender of the individual (1: Male, 0: Female).
- **ChestPainType**: Type of chest pain experienced (e.g., typical angina, atypical angina).
- **RestingBP**: Resting blood pressure (mm Hg).
- **Cholesterol**: Serum cholesterol (mg/dl).
- **FastingBS**: Fasting blood sugar (> 120 mg/dl, 1: True, 0: False).
- **RestingECG**: Resting electrocardiographic results.
- **MaxHR**: Maximum heart rate achieved.
- **ExerciseAngina**: Exercise-induced angina (1: Yes, 0: No).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: Slope of the peak exercise ST segment.
- **Ca**: Number of major vessels colored by fluoroscopy (0-3).
- **Thal**: Thalassemia (Normal, Fixed Defect, Reversible Defect).
- **Target**: Target variable (1: Heart Disease, 0: No Heart Disease).

---

## Tools and Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Pandas (Data manipulation and analysis)
  - NumPy (Numerical computing)
  - Scikit-learn (Machine learning)
  - Matplotlib/Seaborn (Data visualization)
- **Environment**: Jupyter Notebook or any Python IDE

---

## Model Development Workflow

1. **Data Preprocessing**:
   - Handle missing values.
   - Normalize/scale the features.
   - Split data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze correlations between features.
   - Visualize feature distributions.

3. **Model Selection and Training**:
   - Experiment with algorithms like Logistic Regression, SVM.

4. **Evaluation Metrics**:
   - Accuracy
   - Precision

## Future Improvements

- Incorporate additional features like lifestyle habits and medical history.
- Experiment with advanced models like Neural Networks.
- Deploy the model using Flask or FastAPI for real-time predictions.

---

## Acknowledgments

- **Dataset**: [Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)



