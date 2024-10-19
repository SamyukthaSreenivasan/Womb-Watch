# Womb-Watch
WombWatch is a predictive healthcare application designed to monitor fetal development by analyzing maternal and fetal health data. This project aims to empower healthcare providers and expectant mothers with actionable insights for better prenatal care.

## Table of Contents

- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Datasets](#datasets)
- [Experiments](#experiments)
- [Future Improvements](#future-improvements)
- [Code Implementation](#code-implementation)

## Problem Statement

The project addresses the challenge of monitoring fetal health in real-time, enabling early detection of potential risks during pregnancy through data-driven insights.

## Solution Overview

We integrate maternal and fetal datasets using machine learning algorithms to predict fetal health outcomes.

## Datasets

- **Maternal Health Dataset**: Contains maternal health indicators such as age, blood pressure, and risk levels.
- **Fetal Health Dataset**: Includes features related to fetal health, such as fetal movements, uterine contractions, and other vital signs.
- **Future Datasets**: Plans to incorporate CT scans and other relevant medical datasets for improved prediction accuracy.

## Experiments

1. **Model Training**: 
   - Various models were tested, including Random Forest and Gradient Boosting.
   - Achieved a prediction accuracy of approximately **94%** for fetal health outcomes.

2. **Feature Importance Analysis**: 
   - The most important features identified include `abnormal_short_term_variability` and `fetal_movement`.

3. **Evaluation Metrics**: 
   - Classification reports and accuracy metrics were generated to assess model performance.
  
## Future Improvements:
1. **Streamlit Integration:**
Develop an interactive web application using Streamlit to allow healthcare providers and mothers to easily input data, visualize results, and access predictions in real-time.

2. **Expanded Dataset Integration:**
Incorporate additional datasets such as CT scans, ultrasound images, or genetic data to enhance predictive capabilities and provide more comprehensive insights into fetal health.

3. **Real-Time Data Processing:**
Implement functionality for real-time data streaming and analysis from wearable devices or mobile applications to monitor maternal and fetal health continuously.

4. **Advanced Machine Learning Technique**
Experiment with more complex machine learning models, such as deep learning (e.g., convolutional neural networks) for image data analysis, or ensemble methods to improve prediction accuracy.

5. **User Personalization:**
Develop personalized health tracking and notification features for users based on their specific health conditions and history.

## Code Implementation:
![image](https://github.com/user-attachments/assets/bf50a263-f878-49df-bd77-4dcfb236a837)

![image](https://github.com/user-attachments/assets/331ecedf-97f3-4f34-b0d8-164159bb52b2)

![image](https://github.com/user-attachments/assets/2dad91ac-b602-4f1f-b585-eb8290f7fb1d)

## Results

The WombWatch project aims to analyze fetal health data and provide predictive insights based on the analysis. Here are some key results obtained from our model:

### Model Performance
- **Accuracy**: 94.1%
- **Classification Report**:
  - **Class 1 (Normal)**:
    - Precision: 0.96
    - Recall: 0.98
    - F1-Score: 0.97
  - **Class 2 (Suspicious)**:
    - Precision: 0.88
    - Recall: 0.77
    - F1-Score: 0.82
  - **Class 3 (Pathological)**:
    - Precision: 0.87
    - Recall: 1.00
    - F1-Score: 0.94

### Feature Importance
- The most important feature for predicting fetal health was **abnormal_short_term_variability**.
- The least important feature was **severe_decelerations**.

### Conclusion
The WombWatch model shows promising results in predicting fetal health based on various metrics. Future improvements can include the integration of additional datasets and enhancement of the user interface for better accessibility.
