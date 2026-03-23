# Fault-Detection-Using-ML
Developed a hybrid ML + Digital Twin framework for fault diagnostics in PV power plants, enabling anomaly detection, fault classification, and prioritization using SVM and XGBoost on large-scale simulated data (~700K samples).

A 250 kW PV system is modeled in MATLAB Simulink to generate simulated operational data. Machine learning algorithms are then applied to detect anomalies, classify faults, and prioritize them efficiently.

Key Features:
Anomaly Detection using ML models
Fault Classification (multiple fault types)
Priority-based Fault Diagnostics
Real-time monitoring via Simulink dashboard
Integration of Digital Twin + Machine Learning

Dataset Details
Total Data Points: 700,000
  Healthy Data: 500,000
  Faulty Data: 200,000

Features Used:
Irradiance
Temperature
DC Current
DC Voltage
DC Power
Grid Current
Grid Power

Fault Labels:
0 → Healthy
1 → Open Circuit Fault
2 → Short Circuit Fault
3 → Irradiance Variation
4 → Temperature Variation

Machine Learning Models
Support Vector Machine (SVM)
Extreme Gradient Boosting (XGBoost)

Methodology
Design PV system using MATLAB Simulink (Digital Twin)
Simulate normal and fault conditions
Generate and label dataset
Preprocess and normalize data
Train ML models (SVM + XGBoost)
Evaluate model performance
