# IOT-ML-PROJECT
IOT BASED SMART HEALTH WEARABLE WITH MACHINE LEARNING ANOMALIES 
-This project presents an IoT-based wearable health monitoring system designed for real-time tracking of vital physiological parameters and automated anomaly detection using Machine Learning.
The system uses biomedical sensors interfaced with an ESP8266 microcontroller to collect health data and transmit it to Firebase for cloud storage and monitoring. A Random Forest classifier is implemented to detect abnormal physiological patterns.

Features -

1)Real-time monitoring of:
2)Heart Rate
3)Blood Pressure
4)SpO₂ (Oxygen Saturation)
5)Step Count
6)Wi-Fi data transmission using ESP8266
7)Cloud storage via Firebase Realtime Database
8)Machine Learning-based anomaly detection
9)Remote monitoring capability

System Architecture -
Biomedical sensors capture physiological signals.
ESP8266 processes and transmits data over Wi-Fi.
Data is stored in Firebase Realtime Database.
Random Forest model analyzes incoming data.
Anomalies are flagged for monitoring or intervention.

Tech Stack -
Hardware
ESP8266 (NodeMCU)
Blood Pressure Sensor
SpO₂ Sensor (MAX30100 / MAX30102)
Heart Rate Sensor
Accelerometer / Step Counter
Software
Arduino IDE (Embedded C/C++)
Python
Scikit-learn (Random Forest)
Firebase Realtime Database
Machine Learning Model

Algorithm: Random Forest Classifier
Input Features: Heart Rate, Blood Pressure, SpO₂, Step Count
Output Classes: Normal / Anomaly
The model was selected for its robustness to noise, ability to handle multivariate health data, and reduced overfitting compared to single decision trees.
Applications
Remote patient monitoring
Elderly health supervision
Preventive healthcare systems
Smart wearable health analytics
Future Work
LSTM-based temporal anomaly detection
Mobile application integration
Real-time alert system (SMS/Email)
Edge AI deployment
