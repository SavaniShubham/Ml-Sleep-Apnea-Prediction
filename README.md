# Ml-Sleep-Apnea-Prediction

📌 Project Overview

This project aims to build a machine learning model that predicts whether an individual is likely to have sleep apnea using health, demographic, and lifestyle features. This can assist in early identification of individuals at risk, improving timely medical intervention

📂 Dataset Used

Features:

•	Age
•	Alcohol/Smoking Addiction
•	Daily Steps
•	Heart Rate
•	Stress Level
•	Sleep Duration
•	Sleep Quality
•	Quality of Sleep
•	Screen Time
•	Screen Time (before Sleep)
•	Physical Activity Level
•	Systolic and Diastolic Blood Pressure
•	BMI Category (Normal Weight, Overweight, Obese)
•	Sleep Disorders (e.g., Insomnia, Parasomnia, Restless Leg Syndrome)
•	Sleep Walking
•	Occupation
•	Gender

Target Variable:

 Sleep Disorder_Sleep Apnea
 
🏆 Model Chosen

Logistic Regression: Chosen for its simplicity and effectiveness in binary classification problems.
K-Nearest Neighbors (KNN) – For comparison using distance-based classification 

🔬 Data Preprocessing

Handling Missing Values
Encoding Categorical Variables 
Feature Scaling 
Train-Test Split

📊 Performance Metrics

Accuracy Score
Confusion Matrix
Classification Report (Precision, Recall, F1-Score)

Project Structure
├── data                    #dataset
├── models/                 # Saved models
├── src/                    # training model and ML code
├── requirements.txt        # Dependencies
├── LICENSE                 # Open-source license
├── README.md               # Project overview
└── docs/                   # Additional documentation

