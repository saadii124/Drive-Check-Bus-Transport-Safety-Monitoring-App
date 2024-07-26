# Drive-Check-Bus-Transport-Safety-Monitoring-App

# Project Overview
Drive Check is an innovative mobile application designed to enhance the safety and efficiency of bus transportation systems. This app aims to provide real-time monitoring of driver behavior to prevent accidents caused by overspeeding, drowsiness, and other distractions. By leveraging advanced AI and machine learning models, Drive Check offers a comprehensive solution for bus transport company owners and management heads to ensure the safety of their fleet and passengers.

# Features
Real-Time Monitoring: Utilizes mobile phone cameras for real-time monitoring of driver drowsiness.<br>
Overspeeding Detection: Monitors bus speed through OpenStreetMap (OSM) integration.<br>
Alert Mechanism: Sends immediate notifications to transport company owners when safety violations are detected.<br>
Driver Dashboard: Provides detailed information on driver behavior and location tracking.<br>
# Implementation Details
# Algorithm Development and Speed-o-Meter
We have developed a custom algorithm using the YOLOv8 model to detect driver drowsiness. The model was trained on a dataset of drowsiness images and tested to ensure high accuracy. The overspeeding detection is implemented using the OpenStreetMap (OSM) library to track the bus location and speed.

# System Integration
The system integrates various components, including the mobile application, AI models, and a cloud-based database (Firebase). The mobile app captures real-time video, processes it using the trained AI model, and updates the status to Firebase.

# Alert Mechanism Implementation
An alert mechanism is in place to notify transport company owners of any detected issues. The system sends push notifications in real-time to ensure immediate action can be taken.

# Testing and Validation
The system was thoroughly tested using multiple scenarios to validate its effectiveness. The AI model for drowsiness detection was tested using live camera feeds, ensuring it accurately identifies drowsy drivers.

# Deployment and Evaluation
The app is ready for deployment on Android devices running OS 8.0 (Oreo) and above. The deployment process includes setting up Firebase for data storage and notification services.

# Mobile Application Development
The mobile app was developed using Android Studio and Kotlin. The UI/UX design focuses on ease of use and providing clear, actionable information to the user. The app integrates OpenStreetMap for location tracking and uses Google Mobile Vision API for real-time video analysis.

# Future Work
Future enhancements include integrating onboard cameras in buses for better monitoring and deploying the trained drowsiness detection model into the mobile app. Additional features such as distracted driving detection and more sophisticated alert mechanisms will also be explored.

# Sustainable Development Goals (SDGs)
Our project aligns with the following SDGs:

Good Health and Well-Being: By enhancing road safety, we aim to reduce accidents and injuries.<br>
Decent Work and Economic Growth: Ensuring safe transport systems contributes to economic stability.<br>
Industry, Innovation, and Infrastructure: Drive Check promotes innovation in transportation safety.<br>
# Tools and Techniques
Programming Languages: Kotlin for Android development<br>
Machine Learning Models: YOLOv8 for drowsiness detection<br>
APIs: Google Mobile Vision API for real-time video analysis<br>
Mapping: OpenStreetMap for location tracking<br>
Database: Firebase for data storage and notifications<br>
Development Environment: Android Studio<br>
# Contact
For more information, please contact the project team at [drivecheck727@gmail.com].
# Screenshots
![logo](https://github.com/user-attachments/assets/ee134ea0-3f2f-4a18-b6e0-f550af1f6340)
![logging(loading)](https://github.com/user-attachments/assets/4b786e5d-9fad-44c3-9a3f-d69c1808a2ea)
![driver detail(not drowzy_online)](https://github.com/user-attachments/assets/663fde95-878c-4994-b8a6-fb3d54adef99)
![driver detail(map)](https://github.com/user-attachments/assets/62c18644-0ad7-4e39-9690-8f4d3031f1ab)
![driver dashboard](https://github.com/user-attachments/assets/fde5c177-d049-4174-89c0-61b8c36c937c)
![signup(owner)](https://github.com/user-attachments/assets/51bd6165-d444-4149-8edc-45eeec3bfddb)
![signup(dr)](https://github.com/user-attachments/assets/d891c07f-24ec-4a5a-bc41-c45e3dc357aa)
![owner dashboard](https://github.com/user-attachments/assets/502c6338-2743-4c15-aaab-18b1c89850af)
![login](https://github.com/user-attachments/assets/1eb58248-81cd-4b4e-8503-4293675527ab)

