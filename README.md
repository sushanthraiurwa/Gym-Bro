📌 AI-Powered Posture Detection & Fitness Guidance App

This project is a mobile application built using Flutter, MediaPipe, and Firebase that provides real-time posture detection, exercise recognition, and corrective workout feedback. The app helps users perform exercises safely and effectively using only their smartphone camera.

🚀 Overview

Artificial Intelligence is transforming the fitness industry, enabling intelligent exercise analysis beyond simple step or calorie tracking.
This mobile app uses Human Pose Estimation (HPE) and Human Action Recognition (HAR) to detect body posture in real time and guide users toward proper workout form.

The goal is to provide expert-level training assistance, reduce injuries, and enhance workout performance—without needing a personal trainer or expensive equipment.

⚠️ Problem Statement

Traditional fitness apps lack intelligence and cannot provide real-time posture correction. Users often perform exercises incorrectly, leading to injuries and ineffective workouts.

Challenges in current systems include:

Occlusion: Body parts may get hidden during movement.

Domain Gap: Lab-trained ML models struggle in real-world environments.

Limited Personalization: Standard models fail to adapt to different body types or poses.

This project aims to overcome these challenges using on-device pose estimation and exercise analysis, making fitness guidance accessible to everyone.

🎯 Objectives

Detect human posture in real time using MediaPipe Pose

Recognize and classify common exercises based on movement

Provide instant corrective feedback for proper form

Track exercise metrics such as reps, sets, and pose accuracy

Store user workout results using Firebase (Firestore/Storage)

🔧 Functionalities of the Modules
1. Camera & Pose Detection Module

Captures live video through the phone’s camera

Uses MediaPipe Pose / Holistic to detect 33+ body landmarks

Tracks joint movement frame-by-frame

2. Posture Analysis & Feedback Module

Compares real-time pose with ideal exercise posture

Detects mistakes such as:

Incorrect back angle

Wrong knee alignment

Incomplete movement

Provides instant corrective feedback on screen

3. Exercise Recognition Module

Identifies different exercises (squats, pushups, lunges, etc.)

Tracks:

Reps

Sets

Exercise duration

Form accuracy

4. Results & Analytics Module

Displays user performance after each workout session

Shows metrics like:

Number of reps

Pose accuracy

Detected errors

Stores session results in Firebase Firestore

5. App Interface Module

Built using Flutter

Clean UI with smooth navigation

Real-time camera preview & overlay landmarks

Results screen and analytics charts

🖥️ Software Requirements

Flutter SDK

Dart

Android Studio / VS Code

MediaPipe Pose / MediaPipe Holistic

Firebase (Firestore, Storage)

OpenCV (optional for image processing)

💻 Hardware Requirements

Android smartphone with working camera

Minimum 3–4 GB RAM

Development PC/Laptop with:

Intel i5/Ryzen 5 or above

8–16 GB RAM

Android Studio installed

📦 Tech Stack
Component	Technology Used
Frontend	Flutter (Dart)
AI Model	MediaPipe Pose / Holistic
Processing	On-device ML pipeline
Database	Firebase Firestore
Storage	Firebase Cloud Storage