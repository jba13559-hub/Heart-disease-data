# Heart Disease Prediction

## Project Overview
This project aims to predict the presence of heart disease in patients using machine learning classification techniques. The objective is to analyze patient health records, identify important risk factors, and build predictive models that can assist in the early detection of heart disease.

## Dataset Description
The dataset contains various medical and clinical attributes of patients, including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate Achieved
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- Other cardiovascular indicators

### Target Variable
- **0** = No Heart Disease
- **1** = Heart Disease

## Data Preprocessing
To ensure high-quality model performance, the following preprocessing steps were performed:

- Data cleaning and validation
- Missing value handling
- Outlier treatment using capping techniques
- Feature scaling and normalization
- Exploratory Data Analysis (EDA)
- Training and testing data split

## Exploratory Data Analysis
Several visualizations were created to understand data distributions, detect outliers, and analyze relationships between features and the target variable:

- Histograms
- Box Plots
- Count Plots
- Correlation Heatmaps
- Feature Distribution Analysis

### Key Insights
- Chest pain type showed a strong relationship with heart disease occurrence.
- Patients with lower maximum heart rates were more likely to have heart disease.
- Certain clinical measurements exhibited significant correlations with the target variable.
- Outlier treatment improved data quality while preserving important medical information.

## Machine Learning Models
The following classification models were trained and evaluated:

1. Logistic Regression
2. Decision Tree Classifier
3. K-Nearest Neighbors (KNN)

## Model Evaluation
Models were assessed using multiple evaluation metrics:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

## Results
Among all models, **Logistic Regression** achieved the best overall performance and demonstrated a balanced trade-off between precision and recall. The model successfully identified heart disease cases while maintaining reliable classification performance, making it the most suitable choice for this dataset.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
heart-disease-prediction/
│
├── Heart_Disease_Prediction.ipynb
├── README.md
└── dataset.csv
```

## Learning Outcomes
Through this project, I gained practical experience in:

- Data cleaning and preprocessing
- Outlier detection and treatment
- Exploratory Data Analysis (EDA)
- Feature scaling techniques
- Classification model development
- Model evaluation and comparison
- Healthcare data analysis using machine learning

## Conclusion
This project demonstrates how machine learning can be applied to healthcare data to predict heart disease risk. By combining data preprocessing, visualization, and classification techniques, meaningful patterns were identified, and a reliable predictive model was developed. The project highlights the importance of data-driven approaches in supporting medical decision-making and early disease detection.
