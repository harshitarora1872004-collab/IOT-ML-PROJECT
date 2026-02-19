# IOT-ML-PROJECT
IOT BASED SMART HEALTH WEARABLE WITH MACHINE LEARNING ANOMALIES 
-This project presents an IoT-based wearable health monitoring system designed for real-time tracking of vital physiological parameters and automated anomaly detection using Machine Learning.
The system uses biomedical sensors interfaced with an ESP8266 microcontroller to collect health data and transmit it to Firebase for cloud storage and monitoring. A Random Forest classifier is implemented to detect abnormal physiological patterns.
![WhatsApp Image 2026-02-19 at 7 13 13 PM](https://github.com/user-attachments/assets/08f2bbb1-eb1d-4032-a83f-6f4b6fc1c604)


Components 

MAX30100 Pulse Oximeter
![WhatsApp Image 2026-02-19 at 7 13 13 PM (1)](https://github.com/user-attachments/assets/2c55c6e0-0688-41b1-a3fe-afe7f8f77fcf)

DHT11 Sensor Module 
![WhatsApp Image 2026-02-19 at 7 13 14 PM](https://github.com/user-attachments/assets/0ff00114-8065-4cdc-91e4-c3d888f7e32f)


MPU
![WhatsApp Image 2026-02-19 at 7 13 14 PM (1)](https://github.com/user-attachments/assets/5891e87d-b548-426d-b129-2ec3f04aa049)


GPS ANTENNA and Module

NEO-6M GPS Module , Ceramic GPS Antenna
![WhatsApp Image 2026-02-19 at 7 13 14 PM (2)](https://github.com/user-attachments/assets/d8153bb7-542b-45b6-bb15-ae2b5556a904)

ESP8266 NodeMCU , MAX30100 Sensor
![WhatsApp Image 2026-02-19 at 7 13 15 PM](https://github.com/user-attachments/assets/c9618a96-a931-43d9-ba2a-91c0f812bc15)


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

4) SpO₂ Sensor (MAX30100)

5) Heart Rate Sensor

6) Accelerometer / Step Counter

Software -

1) Arduino IDE (Embedded C)

2) Python

3) Scikit-learn (Random Forest)

4) Firebase Realtime Database

5) Machine Learning Model

Algorithm: Random Forest Classifier

Input Features: Heart Rate, Blood Pressure, SpO₂, Step Count

Output Classes: Normal / Anomaly

The model was selected for its robustness to noise, ability to handle multivariate health data, and reduced overfitting compared to single decision trees.

Applications -

1) Remote patient monitoring

2) Elderly health supervision

3) Preventive healthcare systems

4) Smart wearable health analytics

5) Future Work

6) LSTM-based temporal anomaly detection

7) Mobile application integration

8) Real-time alert system (SMS/Email)

9) Edge AI deployment
