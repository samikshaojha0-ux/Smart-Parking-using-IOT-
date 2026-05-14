# 🅿️ Smart Parking System using IoT & Android

> A mobile + IoT-based Smart Parking System (SPMS) that helps drivers find available parking slots in real-time — reducing traffic congestion, fuel waste, and manual labor.

---

## 📌 Project Overview

This project implements an integrated Smart Parking System using **Android Studio**, **Firebase**, **IoT sensors**, and **Razorpay** payments.  
Drivers can find and book available parking slots from anywhere via a mobile app, while IR sensors monitor real-time slot availability.

**Developed as part of Mini Project — AY Even 2023-24**  
Department of Computer Science & Engineering (Data Science)  
Guided by: Vrushali Bendre

---

## 🚗 Problem It Solves

- Drivers waste significant time searching for parking in crowded areas
- No way to know if a parking slot is available without physically checking
- Manual labor required to manage existing parking arrangements
- Traffic congestion caused by vehicles circling in search of parking

---

## ✅ Key Features

- 📱 **Mobile App** (Android) — Find and book parking slots from anywhere
- 🔐 **User Registration & OTP Verification** — Phone number validation via OTP
- 🟢 **Real-Time Slot Availability** — Live updates using IoT sensors
- 💳 **Online Payments** — Integrated Razorpay payment gateway
- 🔥 **Firebase Backend** — Real-time database for slot status updates
- 📡 **IoT Sensors** — IR/proximity sensors detect slot occupancy

---

## 🛠️ Tech Stack

| Category | Technology |
|---|---|
| Mobile App | Android Studio |
| Backend / Database | Firebase Realtime Database |
| Payment Gateway | Razorpay |
| IoT Hardware | IR Sensors, Wi-Fi Modules |
| Language | Java / XML (Android) |

---

## ⚙️ System Architecture

```
[IR Sensors] → [Wi-Fi Module] → [Firebase Database] → [Android App] → [User]
                                                              ↓
                                                       [Razorpay Payment]
```

1. IR sensors detect whether a parking slot is occupied or vacant
2. Data sent via Wi-Fi module to Firebase in real time
3. Android app reads Firebase and displays live slot availability
4. User selects a slot → makes payment via Razorpay → parks vehicle

---

## 📱 App Screenshots

| Screen | Description |
|---|---|
| Loading Page | App splash/loading screen |
| Registration Page | User signs up with phone number |
| OTP Verification | Phone number validated via OTP |
| Home Page | Displays available slots after login |
| Slot Selection | User selects and books a parking slot |

---

## 🔑 Key Benefits

- ⏱️ Saves time — drivers know slot availability before arriving
- ⛽ Reduces fuel waste from unnecessary searching
- 🚦 Decreases traffic congestion in public areas
- 👷 Reduces need for manual parking attendants
- 🌍 Environmentally friendly — less emissions from circling vehicles

---

## 🔮 Future Scope

- Integration with actual IR/ultrasonic/PIR/motion sensors on-site
- Predictive availability using ML models
- Multi-city parking network
- Navigation integration (Google Maps)

---
## 👩‍💻 Author

**Samiksha S Ojha**  
B.E. Computer Science Engineering (Data Science) — Lokmanya Tilak College of Engineering  
[LinkedIn](https://linkedin.com/in/samiksha-ojha) • [GitHub](https://github.com/samikshaojha0-ux)
|


## 📚 References

- Loai Kayed et al., 2023 — Smart-parking management algorithms in smart city
- Yash M Dala, Dr. Kumar Raj, 2023 — Eco Park: A Low-Cost and Sustainable Approach for Smart Parking Systems

