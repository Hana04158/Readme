# 🏠 IoT-Based Smart Home System with Photovoltaic Integration and Battery Storage
[![ESP32](https://img.shields.io/badge/ESP32-IoT-blue)](https://www.espressif.com/en/products/socs/esp32)
[![Flutter](https://img.shields.io/badge/Flutter-Mobile_App-02569B)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-Database-orange)](https://firebase.google.com)
[![MQTT](https://img.shields.io/badge/MQTT-HiveMQ-purple)](https://www.hivemq.com/mqtt/)
[![Solar](https://img.shields.io/badge/Solar-Powered-green)](YOUR_GITHUB_PAGES_LINK)
[![LinkedIn](https://img.shields.io/badge/Team-LinkedIn-0A66C2)](YOUR_LINKEDIN_LINK)
[![Documentation](https://img.shields.io/badge/Project-Documentation-red)](YOUR_README_LINK)

<p align="center">
  <img src="https://github.com/user-attachments/assets/cdc88c2e-5277-47d5-9b25-f4214de6eb51" width="300"/>
</p>
<p align="center">
Smart Automation • Renewable Energy • Real-Time Monitoring
</p>

## 💡 The Idea

Modern homes consume large amounts of energy every day, often without efficient monitoring or intelligent control. Many appliances continue operating unnecessarily, renewable energy systems are not fully optimized, and traditional smart home solutions frequently rely on fragmented architectures with limited automation capabilities.

This project was developed to address these challenges by creating a unified smart home platform that combines IoT automation, renewable energy integration, intelligent load management, and real-time mobile monitoring into a single efficient system.

## ⚙️ What Our System Does

The proposed smart home system continuously monitors the residential environment using multiple sensors connected to ESP32 microcontrollers. The system tracks:

- Temperature and humidity of the house
- Motion and occupancy inside the house
- Gas leakage and smoke detection for safety
- Rain conditions
- Energy consumption and battery status

Based on these readings, the system can automatically control household appliances such as:
- Lighting systems
- Cooling fans
- Water pumps
- Garage and entrance doors
- Safety alarms

All devices can also be remotely controlled through a Flutter mobile application.

## 🧩 System architecture

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/bdb43ffe-9331-48eb-9f13-ec91ae260b07" />


## ☀️ Renewable Energy Integration

To improve sustainability and reduce electricity consumption, the system integrates photovoltaic (PV) solar panels with lithium-ion battery banks as storage.

The generated solar energy powers the smart home loads during daytime operation, while excess energy is stored in batteries to support nighttime operation. Intelligent load-priority management ensures that critical devices continue operating even under limited energy availability.

The implemented energy-management strategy successfully reduced energy consumption while maintaining user comfort.

## 📡 Communication and Connectivity

The system uses the MQTT communication protocol with the HiveMQ cloud broker to enable fast and reliable communication between:

- ESP32 controllers
- Sensors
- Household loads
- Flutter mobile application

A dual-SSID fallback mechanism was also implemented to improve network resilience and maintain uninterrupted monitoring during Wi-Fi interruptions.

## 📱 Mobile Application

The Flutter mobile application acts as the central control dashboard of the system. Through the app, users can:

- Monitor live sensor readings
- Control appliances remotely
- Receive instant safety notifications
- View historical energy-consumption graphs
- Enable automatic or manual operation modes

Firebase services are integrated for real-time synchronization and historical data logging.

## 📈 Results
The implemented prototype successfully demonstrated:

- Real-time remote monitoring
- Intelligent load control
- Reliable safety notifications
- Efficient solar-energy utilization

The system achieved approximately:

# ⚡ 72.3% Energy Reduction

---

## 👨‍💻 Team Members
- Hana Ghallab
- Sara Azary
- Maryam ELl-Khatib
- Alia El-Nagar
- Ann Anbar
