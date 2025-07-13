# Osteoporosis Risk Prediction

This project aims to leverage machine learning to predict the risk of osteoporosis based on various clinical and lifestyle factors. By analyzing data such as age, gender, physical activity, calcium intake, and medical history, the goal is to develop a predictive model that can help identify individuals who may be at a higher risk of developing osteoporosis, enabling timely interventions and preventive measures.

## Dataset

The dataset used for this project contains 15 features, including demographic information, medical history, and lifestyle habits, with a total of 1,958 records. Key features include:

- **Age**
- **Gender**
- **Body Mass Index (BMI)**
- **Calcium Intake**
- **Physical Activity Levels**
- **Medical Conditions** (e.g., arthritis, liver condition)
- **Family History of Osteoporosis**
- **Prior Fractures**

## Methodology

### Data Preprocessing

The dataset was cleaned, and missing values were handled. Features were appropriately encoded for model training.

### Model Development

Several machine learning algorithms were applied, including:

- **Logistic Regression**
- **Random Forest Classifier**
- **Decision Tree Classifier**
- **Support Vector Classifier (SVC)**
- **K-Nearest Neighbors (KNN)**

### Model Evaluation

The models were evaluated based on accuracy, precision, recall, and F1-score. The **Decision Tree Classifier** achieved the highest accuracy (~89-91%).

## Key Insights

- **Age**: Older individuals are at higher risk of osteoporosis.
- **Gender**: Women, especially postmenopausal, are at a higher risk.
- **Lifestyle Factors**: Sedentary lifestyle and inadequate calcium intake increase risk.
- **Medical History**: Conditions like arthritis, liver disease, and prior fractures elevate risk.

## Conclusion

This project demonstrates the potential of machine learning to predict osteoporosis risk based on lifestyle and health data. The **Decision Tree Classifier** emerged as the best-performing model, with high accuracy in risk prediction. This model can help healthcare providers in early intervention for individuals at risk of osteoporosis.

For more details and access to the code, visit the [GitHub repository](https://github.com/shuvosharkr/Osteoporosis-Risk-Prediction).
