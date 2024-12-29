# AI-Powered-Fault-Prediction-and-Optimization-in-New-Energy-Vehicles-NEVs-for-the-US-Market
## Project Overview

This project is an in-depth exploration of vehicle fault detection and analysis using a structured dataset of 1000 records. The dataset includes critical parameters such as battery voltage, engine temperature, speed, tire pressure, and other influential metrics. This analysis aims to predict the type of vehicle fault accurately, leveraging advanced machine learning models and professional-grade visualizations.

Modern vehicles generate a vast amount of data through onboard sensors. This data holds the potential to diagnose issues proactively, ensuring timely maintenance and reducing the risk of breakdowns. In this project, we processed the dataset extensively, performed exploratory data analysis (EDA), and applied three powerful classification algorithms: Logistic Regression, Random Forest Classifier, and Gradient Boosting Classifier. Each model's performance was evaluated using precision, recall, F1-score, and accuracy metrics.

Our professional visualizations included time-series plots and heartbeat-style graphs to capture trends and dynamics effectively. These insights empower automotive stakeholders to improve operational efficiency, safety, and decision-making.

## Key Features

- **Data Preparation:**
  - Cleaned and preprocessed the dataset by handling missing values and standardizing numerical features.
  - Encoded categorical variables to make them suitable for machine learning models.
  
- **Machine Learning Models:**
  - Logistic Regression, Random Forest Classifier, and Gradient Boosting Classifier were applied.
  - Detailed performance evaluation using classification reports and accuracy scores.
  
- **Visualizations:**
  - Comprehensive visualizations to highlight trends, patterns, and correlations.
  - Time-series and heartbeat-style plots for engine temperature, tire pressure, and more.

## Results

### Logistic Regression
- **Accuracy:** 35.50%
- **Classification Report:**

```
                    precision    recall  f1-score   support

     battery_issue       0.37      0.89      0.52        76
engine_overheating       0.27      0.09      0.13        34
          no_fault       0.00      0.00      0.00        48
sensor_malfunction       0.00      0.00      0.00        42

          accuracy                           0.35       200
         macro avg       0.16      0.25      0.16       200
      weighted avg       0.19      0.35      0.22       200
```

### Random Forest Classifier
- **Accuracy:** 38.50%
- **Classification Report:**

```
                    precision    recall  f1-score   support

     battery_issue       0.40      0.95      0.56        76
engine_overheating       0.43      0.09      0.15        34
          no_fault       0.40      0.04      0.08        48
sensor_malfunction       0.00      0.00      0.00        42

          accuracy                           0.39       200
         macro avg       0.31      0.27      0.19       200
      weighted avg       0.32      0.39      0.26       200
```

### Gradient Boosting Classifier
- **Accuracy:** 36.50%
- **Classification Report:**

```
                    precision    recall  f1-score   support

     battery_issue       0.40      0.80      0.54        76
engine_overheating       0.36      0.26      0.31        34
          no_fault       0.38      0.06      0.11        48
sensor_malfunction       0.00      0.00      0.00        42

          accuracy                           0.36       200
         macro avg       0.28      0.28      0.24       200
      weighted avg       0.30      0.36      0.28       200
```

## Business Impact

1. **Proactive Fault Detection:**  
   Timely identification of issues like battery failures or engine overheating reduces downtime and operational risks.

2. **Enhanced Maintenance Strategies:**  
   Insights into frequent faults and service requirements enable efficient resource allocation, lowering repair costs.

3. **Increased Safety:**  
   Monitoring critical parameters such as engine temperature and tire pressure minimizes accident risks associated with mechanical failures.

4. **Cost Savings:**  
   Optimized maintenance schedules prevent unnecessary expenses, ensuring fleet operations remain cost-effective.

5. **Customer Satisfaction:**  
   Improved reliability and safety directly translate to better customer experiences, driving long-term loyalty.

## Technologies Used

- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Models:** Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier
- **Visualization Tools:** Matplotlib and Seaborn for dynamic and static plots
