# GuardianWheel Architecture

## Overview

GuardianWheel is an AI-powered driver safety platform that combines real-time fatigue detection with an on-demand replacement driver booking system.

The system continuously monitors the driver's facial behavior using computer vision techniques. When fatigue is detected, the platform alerts the driver and provides access to nearby verified replacement drivers.

## System Components

### 1. Fatigue Detection Module

* OpenCV-based face detection
* Eye Aspect Ratio (EAR) calculation
* PERCLOS monitoring
* Fatigue classification

### 2. Alert Engine

* Audio alerts
* Visual notifications
* Emergency warnings

### 3. Driver Booking Module

* Driver discovery
* Driver verification
* Booking confirmation
* Ride assignment

### 4. GPS Tracking Module

* User location tracking
* Nearby driver identification
* Route visualization

### 5. Emergency SOS Module

* Emergency contact notification
* Live location sharing
* Quick assistance request

### 6. Cloud Backend

* Firebase Authentication
* Firestore Database
* User and driver management

## Technology Stack

Frontend:

* HTML
* CSS
* JavaScript

Backend:

* Flask
* Python

Database:

* Firebase Firestore

AI & Computer Vision:

* OpenCV
* Dlib
* EAR
* PERCLOS

Maps:

* Google Maps API
