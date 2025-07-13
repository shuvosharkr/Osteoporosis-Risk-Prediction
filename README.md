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
- **AdaBoost**
- **XGBoost**
- **Gradient Boosting**
- **Naive Bayes**

### Hyperparameter Tuning

To optimize the performance of the models, **Hyperparameter Tuning** was performed using techniques such as **Grid Search** and **Randomized Search**. This helped to improve the accuracy and overall performance of the models, particularly **Gradient Boosting**, **XGBoost**, and **Random Forest**, among others.

### Model Evaluation

Here are the performance results for each of the models based on various evaluation metrics:

| Model                 | Train Accuracy | Test Accuracy | Precision  | Recall   | F1 Score  | ROC AUC   |
|-----------------------|----------------|---------------|-----------|----------|-----------|-----------|
| KNN                   | 0.7503         | 0.6633        | 0.6374    | 0.6374   | 0.6374    | 0.6615    |
| Decision Tree         | 0.9553         | 0.8699        | 0.8325    | 0.9011   | 0.8654    | 0.8720    |
| Logistic Regression   | 0.8352         | 0.8852        | 0.9255    | 0.8187   | 0.8688    | 0.8808    |
| SVC                   | 0.8506         | 0.8827        | 0.9533    | 0.7857   | 0.8614    | 0.8762    |
| Random Forest         | 0.8806         | 0.8852        | 0.9419    | 0.8022   | 0.8665    | 0.8797    |
| AdaBoost              | 0.9061         | 0.9464        | 1.0000    | 0.8846   | 0.9388    | 0.9423    |
| XGBoost               | 0.9068         | 0.9388        | 0.9817    | 0.8846   | 0.9306    | 0.9352    |
| Gradient Boosting     | 0.9061         | 0.9464        | 1.0000    | 0.8846   | 0.9388    | 0.9423    |
| Naive Bayes           | 0.8429         | 0.8878        | 0.9259    | 0.8242   | 0.8721    | 0.8835    |

The **AdaBoost** and **Gradient Boosting** models performed the best in terms of F1 score (1.0000) and ROC AUC (0.9423). These models showed excellent performance after hyperparameter tuning.

## Key Insights

- **Age**: Older individuals are at higher risk of osteoporosis.
- **Gender**: Women, especially postmenopausal, are at a higher risk.
- **Lifestyle Factors**: Sedentary lifestyle and inadequate calcium intake increase risk.
- **Medical History**: Conditions like arthritis, liver disease, and prior fractures elevate risk.

## Conclusion

This project demonstrates the potential of machine learning to predict osteoporosis risk based on lifestyle and health data. The **AdaBoost** and **Gradient Boosting** classifiers emerged as the top-performing models, with high accuracy in risk prediction. These models can help healthcare providers in early intervention for individuals at risk of osteoporosis.

For more details and access to the code, visit the [GitHub repository](https://github.com/shuvosharkr/Osteoporosis-Risk-Prediction).
