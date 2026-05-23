# ArrivaX – Smart Bus Stand Management System

An innovative IoT-based smart transportation solution designed to improve bus scheduling, reduce delays, and enhance passenger convenience using real-time monitoring and cloud-based technologies.

---

# 📌 Project Overview

ArrivaX is a Smart Bus Stand Management System that combines IoT hardware, Firebase cloud services, and an Android mobile application to provide real-time transportation monitoring and intelligent bus stand management.

The system uses ESP32 microcontrollers, ultrasonic sensors, and Firebase Realtime Database to monitor bus arrivals, calculate delays, detect slot occupancy, and synchronize live transportation data across the cloud.

Passengers and administrators can view real-time updates, monitor bus performance, manage schedules, and analyze transportation efficiency through the Android application.

---

# 🎯 Objectives

* Provide real-time bus tracking and arrival monitoring
* Reduce passenger waiting uncertainty
* Improve public transportation efficiency
* Enable intelligent bus slot management
* Monitor delayed and on-time buses
* Provide centralized cloud-based transportation management
* Support future smart city transportation systems

---

# Key Features

This system enables:

- ✔️ Real-time bus tracking and status updates
- ✔️ Accurate delay calculation (Current Time vs Scheduled Time)
- ✔️ Early arrival and on-time detection
- ✔️ Slot-based bus stand management (A-01, A-02, A-03…)
- ✔️ Live data synchronization using Firebase
- ✔️ IoT-based LCD display for instant information
- ✔️ Admin panel for managing schedules, slots, and bus details
- ✔️ Admin panel for managing conductors and staff
- ✔️ Admin panel for real-time updates and delay control
- ✔️ Admin panel for monitoring system performance and analytics dashboard
- ✔️ Easy search and filtering of bus details
- ✔️ Performance monitoring (on-time vs delayed buses)
- ✔️ User-friendly interface for quick access
- ✔️ Manual override with “Mark as Delayed” option
- ✔️ Scalable system for future smart city integration

---

# System Architecture

The ArrivaX system consists of:

* ESP32 IoT Controllers
* Ultrasonic Distance Sensors
* LCD Display Units
* Firebase Cloud Database
* Android Mobile Application
* Admin Dashboard System

---

# System Workflow

1. Ultrasonic sensors detect approaching buses
2. ESP32 processes the sensor data
3. System calculates ETA and delay status
4. Bus slot occupancy is updated
5. Firebase synchronizes real-time data
6. LCD displays passenger information
7. Android application retrieves live updates
8. Admin dashboard monitors transportation analytics

---

# Hardware Components

* ESP32 Microcontroller
* Ultrasonic Sensors
* LCD Display Module
* Wi-Fi Connectivity Module (Built-in with ESP32)
* Power Supply Unit
* Smart Bus Slot Structure

---

# Software Technologies

## Mobile Application

* Kotlin
* Android Studio
* MVVM Architecture
* Firebase Authentication
* Firebase Realtime Database
* Firebase Firestore

## Embedded System

* Arduino IDE
* C/C++
* Firebase ESP Client Library
* Wi-Fi Communication Protocol
* NTP (Network Time Protocol)

---

# Functional Modules

## Smart ETA Prediction Module

* Calculates estimated bus arrival time
* Detects delays and early arrivals
* Monitors real-time transportation movement

---

## Smart Slot Management Module

* Detects slot occupancy using ultrasonic sensors
* Displays FREE / OCCUPIED slot status
* Supports multiple smart bus stand lanes
* Displays real-time delay status on LCD displays
* Shows delayed, on-time, and early-arrival bus conditions
* Updates physical IoT display components instantly using Firebase synchronization

---

## Android Application Module

* Passenger registration and secure login
* Conductor and staff management
* Real-time bus stand monitoring
* Schedule and slot management
* Live transportation updates and synchronization
* Displays real-time delay time inside the mobile application
* Shows current bus slot status (Occupied / Empty / Updated in real-time)
* Admin control for updating delay information manually
* Easy search and filtering for buses, schedules, and slots
* Real-time analytics and transportation performance monitoring
  
## Admin Dashboard 

* Manage schedules
* Manage bus slots
* Manage conductors and staff
* Monitor delays and analytics
* View performance dashboard

---

## Cloud Synchronization Module

* Firebase Realtime Database integration
* Real-time cloud synchronization
* Multi-device live updates

---

# Installation & Setup

## Hardware Setup

1. Connect ultrasonic sensors to ESP32
2. Connect LCD display module
3. Configure Wi-Fi connection
4. Power the ESP32 device
5. Mount the bus slot monitoring structure

---

## Android Application Setup

1. Install Android Studio
2. Clone this repository

```bash
git clone https://github.com/Thamasha3/Smart-Bus-Stand-App-ArrivaX.git
```

3. Open the project in Android Studio
4. Add the Firebase `google-services.json` file
5. Sync Gradle dependencies
6. Run the application

---

## Embedded Software Setup

1. Install Arduino IDE

2. Install required libraries:

   * WiFi Library
   * Firebase ESP Client Library
   * LiquidCrystal Library

3. Configure:

   * Wi-Fi credentials
   * Firebase API Key
   * Database URL

4. Upload the code to ESP32

---

# Sample Use Case Scenario

When a bus approaches the smart bus stand:

1. The ultrasonic sensor detects the bus distance

2. ESP32 calculates ETA and delay status

3. The system determines whether the bus is:

   * On Time
   * Delayed
   * Early Arrival

4. Firebase database updates in real-time

5. LCD displays bus information

6. Android app instantly updates the status

Displayed messages may include:

* “Bus Arriving”
* “Bus Delayed (with time)”
* “Bus at Stand”
* “Slot Occupied”

---

# Advantages of the System

Reduces passenger uncertainty
Improves transportation reliability
Provides accurate real-time monitoring
Supports smart transportation infrastructure
Cloud-based scalable solution
Low-cost IoT implementation
Enhances transportation efficiency

---

# Future Enhancements

* GPS-based live bus tracking
* AI-powered delay prediction
* Passenger notification system
* QR ticket integration
* Voice announcement system
* Solar-powered smart bus stand
* Advanced analytics dashboard

---

# Team Information

## Project Name

ArrivaX – Smart Bus Stand Management System

## Team Members

* Thamasha Nethmini
* Gothami Dikmadugoda
* Mihili De Silva

---

# License

This project is developed for academic and research purposes only. Unauthorized commercial use is prohibited without prior permission from the project team.

---

# Contact

For technical inquiries or collaboration:

📧 [nethuthamasha3@gmail.com](mailto:nethuthamasha3@gmail.com)

---

# 🎥 Demo Video

https://github.com/user-attachments/assets/9a4d5c4d-705f-4113-881f-b18296151663


# Tags

#IoT #Firebase #ESP32 #Android #Kotlin #SmartTransport #SmartCity #EmbeddedSystems #NIBM #ArrivaX
