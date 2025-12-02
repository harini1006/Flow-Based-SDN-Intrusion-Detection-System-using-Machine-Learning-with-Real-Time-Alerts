# Intelligent SDN Intrusion Detection System
## Machine Learning–Based Flow Traffic Classification for Secure SDN Networks 
## 📌Overview:
The Intelligent SDN Intrusion Detection System (IDS) is a flow-based traffic classification system designed to enhance the security of Software-Defined Networking (SDN) environments.
It uses Machine Learning models, built using Scikit-learn and deployed through Flask, to classify network flows as Normal or Malicious.

The system supports:

1.Real-time single flow prediction

2.CSV-based bulk log prediction

3.User authentication

4.Admin analytics dashboard with attack distribution charts

The goal is to strengthen SDN security by providing a fast, scalable, and intelligent intrusion detection solution.

## ❗Problem Statement:
SDN environments rely on a centralized controller, making them vulnerable to several attacks such as DDoS, Probing, Spoofing, and Botnet traffic.
Traditional IDS systems face challenges including:

1.High false positives

2.Lack of adaptability to new attacks

3.Heavy dependency on signatures

4.Manual and slow log analysis

5.Inability to scale with high-volume SDN traffic

A Machine Learning–driven IDS is necessary to handle SDN flow datasets efficiently and detect malicious traffic with high accuracy.

## 🎯Objectives:
• Develop a robust ML model to classify SDN flow traffic

• Provide real-time and batch prediction capabilities

• Create a user-friendly web interface for easy usage

• Enable admin monitoring through graphical analytics

• Improve accuracy and reduce false alarms

• Design a scalable system suitable for modern SDN networks.

## Key Features:
### User Features:

• User login and registration

• Single flow prediction

• CSV upload for bulk predictions

• View prediction history

### Admin Features:

• Admin login

• View all user predictions

•Attack distribution charts

• Traffic analysis dashboard

### ML Features:

• Complete preprocessing pipeline

• Trained models: Random Forest, SVM, Logistic Regression, Gradient Boosting

• Best model: Random Forest (91% accuracy)

• Model saved and deployed using pickle

## 🧩System Architecture:
<img width="734" height="492" alt="image" src="https://github.com/user-attachments/assets/54bc34b2-eb2f-43e1-9099-9a53fe73228d" />

## 🗂Modules:
### Data Preprocessing

• Handling missing values

• Removing duplicates and outliers

• Label encoding

• Feature scaling

• Train-test splitting

### ML Model Training

 Evaluation metrics used

• Accuracy

• Precision

• Recall

• F1-score

• Confusion Matrix

The Random Forest Classifier built using Scikit-learn achieved the highest performance (91%).

### Web Application

• User Interface includes:

• Login/Register

• Single flow input

• CSV upload

• History view

Admin Interface includes:

• Complete prediction logs

• Graphical attack analytics

## 🛠Tech Stack

Frontend: HTML, CSS, Bootstrap

Backend: Flask (Python)

Machine Learning: Python, Scikit-learn, Pandas, NumPy

Database: SQLite

## Output:
### Login Page:
<img width="738" height="408" alt="image" src="https://github.com/user-attachments/assets/35e723b6-d865-4422-ac82-60ca9b95ae3f" />

### Home Page:
<img width="1853" height="884" alt="image" src="https://github.com/user-attachments/assets/fb292ed8-6a4a-41c8-920d-39919f4c60db" />

### Prediction Result:
<img width="921" height="512" alt="image" src="https://github.com/user-attachments/assets/28f04f5b-4ba5-4bdc-882a-185f1c3ae488" />

### Admin Dashboard:
<img width="953" height="522" alt="image" src="https://github.com/user-attachments/assets/f5ff4579-6544-4c5e-b00f-bdbe3b746209" />

## 📊Results:
• Achieved 91% accuracy using Random Forest

• Accurate classification of multiple attack types

• User- and admin-friendly web interface

• Analytical dashboard for monitoring threats

## 🔮Future Enhancements:

• Real-time detection using Kafka

• Deep learning models (LSTM, CNN)

• Auto-blocking attacks via SDN controller integration

• Cloud deployment (AWS, Azure)

• Role-based authentication and improved UI

## Author
Harini V
B.Tech – Artificial Intelligence and Data Science




