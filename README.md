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

Good Health and Well-Being: By enhancing road safety, we aim to reduce accidents and injuries.
Decent Work and Economic Growth: Ensuring safe transport systems contributes to economic stability.
Industry, Innovation, and Infrastructure: Drive Check promotes innovation in transportation safety.
# Tools and Techniques
Programming Languages: Kotlin for Android development
Machine Learning Models: YOLOv8 for drowsiness detection
APIs: Google Mobile Vision API for real-time video analysis
Mapping: OpenStreetMap for location tracking
Database: Firebase for data storage and notifications
Development Environment: Android Studio
# Contact
For more information, please contact the project team at [drivecheck727@gmail.com].
