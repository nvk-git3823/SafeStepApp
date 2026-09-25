# 🎀 SafeStep — Elderly Care App and Fall Detection Band 🎀

## ⚙️ Fall Detection & Emergency Alert System Band

SafeStep uses an **ESP32 Super Mini** with an **MPU6050 accelerometer and gyroscope** to continuously monitor movement, acceleration, and orientation. The ESP32 processes the sensor data and detects motion patterns associated with potential falls. When a fall is confirmed, a **piezo buzzer** is activated to provide an immediate local alert.

For remote emergency notifications, SafeStep uses **n8n automation**. The confirmed fall event is sent through a **webhook to n8n**, which automatically sends emergency alerts to the registered guardian through **Email and WhatsApp**.

### 🔧 Components

- **ESP32 Super Mini** — Processes sensor data and runs fall-detection logic
- **MPU6050** — Monitors acceleration, movement, and orientation
- **Piezo Buzzer** — Provides an immediate audible fall alert
- **n8n** — Automates emergency notifications
- **Webhook** — Transfers confirmed fall events to n8n
- **Email & WhatsApp** — Deliver emergency alerts to the registered guardian

## Elder care App

A production-ready Flutter mobile app for elderly care with medicine reminders, SOS emergency alerts, medical history tracking, and emergency contacts.

### Features

- **Medicine reminders** — Add, edit, delete medicines with time-based reminders and local notifications
- **SOS emergency** — One-tap emergency alert that calls primary contact and logs to Firestore
- **Medical history** — Timeline of conditions and notes
- **Emergency contacts** — Add contacts, mark one as primary for SOS
- **Profile** — Name, age, blood type, language (English, Hindi, Marathi)
- **Elder-friendly UI** — Large fonts (≥18px), high contrast, soft pastel colors

### Tech Stack

- **Flutter** (latest stable) + Riverpod + go_router
- **Firebase** — Auth, Firestore, Cloud Messaging
- **Notifications** — flutter_local_notifications, firebase_messaging


# Screenshots:-

## 📱 SafeStep App

<p align="center">
  <img src="https://github.com/user-attachments/assets/333b770a-11fe-435c-a341-9e45f0281162" height="400"/>
  <img src="https://github.com/user-attachments/assets/41318dd7-4bba-400f-8778-f5d898b3c227" height="400"/>
  <img src="https://github.com/user-attachments/assets/1633c3a5-4e31-4a8c-86b4-c758ee3f27b0" height="400"/>
  <img src="https://github.com/user-attachments/assets/c958283d-6aee-442a-b207-5ea3144c96f5" height="400"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/540ea957-28ca-46ad-8e81-0b00f631386c" height="400"/>
  <img src="https://github.com/user-attachments/assets/222152ae-cf3d-4d9e-a106-e9d98dc8b401" height="400"/>
  <img src="https://github.com/user-attachments/assets/dedd4593-eef3-4cda-a373-410790f20963" height="400"/>
  <img src="https://github.com/user-attachments/assets/b28ce11b-b71a-453f-b45c-3d3d9d62b91f" height="400"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0f14ac62-71d5-4d06-9d0f-25735f11b852" height="400"/>
  <img src="https://github.com/user-attachments/assets/ab62dea7-8582-4a08-a6bf-0f999c6b1a6c" height="400"/>
  <img src="https://github.com/user-attachments/assets/94461155-1eec-4ea1-b0c4-2d499c2b6f4f" height="400"/>
  <img src="https://github.com/user-attachments/assets/0dcea9d2-521f-4e05-947b-ad9832a70040" height="400"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/e7595aa9-7f38-4abf-8868-82a438d753d0" height="400"/>
</p>


## ⌚ SafeStep Fall Detection Band

<p align="center">
  <img src="https://github.com/user-attachments/assets/bb475de1-2b10-485a-a48b-bfe3a134a8d9" height="220"/>
  <img src="https://github.com/user-attachments/assets/f9373297-ff50-4054-92da-76e4b505eff6" height="220"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/b7414d6b-4bb6-4b0e-bd82-733a0780661f" height="220"/>
  <img src="https://github.com/user-attachments/assets/7ec40b3a-fa5b-4f70-b881-b4f195a8df71" height="220"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d95b778d-4d1e-4239-a8de-57cb6faf7ec6" height="220"/>
</p>

## 🔗 n8n connection for fall alerts

<p align="center">
  <img src="https://github.com/user-attachments/assets/ba59fe41-c250-4a12-adcd-1489ff681e8c" height="190"/>
  <img src="https://github.com/user-attachments/assets/295bc420-7605-41bc-8126-b4d3f283bd60" height="190"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/d2754e97-8b31-4180-a4c3-cd898201778c" width="750"/>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/8021cdb8-bb3a-49bd-aa9b-68fcd1829252" width="600"/>
</p>
