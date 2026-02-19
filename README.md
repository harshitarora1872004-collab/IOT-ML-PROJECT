# IOT-ML-PROJECT
IOT BASED SMART HEALTH WEARABLE WITH MACHINE LEARNING ANOMALIES 
-This project presents an IoT-based wearable health monitoring system designed for real-time tracking of vital physiological parameters and automated anomaly detection using Machine Learning.
The system uses biomedical sensors interfaced with an ESP8266 microcontroller to collect health data and transmit it to Firebase for cloud storage and monitoring. A Random Forest classifier is implemented to detect abnormal physiological patterns.

Features -

A) Real-time monitoring of:
1) Heart Rate

2) Blood Pressure

3) SpO₂ (Oxygen Saturation)

4) Step Count

B) Wi-Fi data transmission using ESP8266

C) Cloud storage via Firebase Realtime Database

D) Machine Learning-based anomaly detection

E) Remote monitoring capability


System Architecture -

1) Biomedical sensors capture physiological signals.

2) ESP8266 processes and transmits data over Wi-Fi.

3) Data is stored in Firebase Realtime Database.

4) Random Forest model analyzes incoming data.

5) Anomalies are flagged for monitoring or intervention.

Tech Stack -

1) Hardware

2) ESP8266 (NodeMCU)

3) Blood Pressure Sensor

4) SpO₂ Sensor (MAX30100 / MAX30102)

5) Heart Rate Sensor

6) Accelerometer / Step Counter

Software -

1) Arduino IDE (Embedded C/C++)

2) Python

3) Scikit-learn (Random Forest)

Firebase Realtime Database

4) Machine Learning Model

Algorithm: Random Forest Classifier

Input Features: Heart Rate, Blood Pressure, SpO₂, Step Count

Output Classes: Normal / Anomaly

The model was selected for its robustness to noise, ability to handle multivariate health data, and reduced overfitting compared to single decision trees.

Applications 

1) Remote patient monitoring

2) Elderly health supervision

3) Preventive healthcare systems

4) Smart wearable health analytics

5) Future Work

6) LSTM-based temporal anomaly detection

7) Mobile application integration

8) Real-time alert system (SMS/Email)

9) Edge AI deployment
