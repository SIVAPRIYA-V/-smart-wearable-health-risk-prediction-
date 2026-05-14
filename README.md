# Smart Wearable Health Risk Prediction System Using Machine Learning

A machine learning-based healthcare prediction system that analyzes wearable healthcare data and predicts whether a user belongs to a **Low Risk** or **High Risk** health category.

## Project Overview

This project uses wearable healthcare data collected from devices such as smartwatches, fitness bands, and health trackers. The system applies multiple machine learning algorithms to predict health risk levels based on physiological and behavioral parameters.

The project focuses on:

* Preventive healthcare monitoring
* Early health risk detection
* Intelligent healthcare analysis
* Machine learning-based prediction

---

## Features

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Multiple machine learning models
* Model evaluation and validation
* Hyperparameter tuning
* Feature importance analysis
* Health risk prediction system

---

## Dataset Information

The dataset contains healthcare-related information collected from wearable devices.

### Main Features

* Heart Rate
* Sleep Hours
* Stress Index
* Physical Activity
* Calories Burned
* Oxygen Level

### Target Variable

* `0` → Low Risk
* `1` → High Risk

### Dataset Details

* Total Rows: 1000
* Total Features: 13
* Problem Type: Binary Classification

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## Machine Learning Algorithms Used

* Logistic Regression
* Decision Tree
* Random Forest Classifier
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)

Among all models, the **Random Forest Classifier** achieved the best accuracy and performance.

---

## Dataset Loading

```python
import pandas as pd

# Load dataset
df = pd.read_csv("wearable_health_data.csv")

# Display first 5 rows
print(df.head())
```

---

## Model Evaluation Metrics

The project uses the following evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* AUC Score

---

## Project Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Model Building
6. Model Training
7. Model Evaluation
8. Cross Validation
9. Hyperparameter Tuning
10. Final Prediction

---

## Advantages

* Early health risk detection
* Intelligent healthcare monitoring
* Automated healthcare analysis
* Improved healthcare decision-making
* Supports preventive healthcare systems

---

## Real-Time Applications

* Smart healthcare systems
* Telemedicine platforms
* Fitness monitoring applications
* Elderly healthcare monitoring
* IoT-based healthcare systems

---

## Future Enhancements

* IoT Integration
* Deep Learning Models
* Cloud-Based Healthcare Analytics
* Mobile Healthcare Application
* Real-Time Wearable Connectivity

---

## Conclusion

This project demonstrates how machine learning and wearable healthcare technologies can work together to improve preventive healthcare systems. The Random Forest model provided reliable and accurate predictions for healthcare risk analysis.

---

## References

* WHO
* Kaggle Dataset
* Google Scholar
* Research Articles on Wearable Healthcare Technology
* Machine Learning by Tom M. Mitchell
