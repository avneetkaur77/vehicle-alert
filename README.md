# 🚗 QR-Based Smart Parking Alert System

## 📌 Overview

This project is a **web-based vehicle alert system** that helps people notify vehicle owners when their car is blocking, incorrectly parked, or causing inconvenience.

Users can scan a **QR code placed on a vehicle** and instantly send a predefined alert via WhatsApp — without needing to search for the owner.

---

## 🚀 Features

* 🔳 **QR Code-Based Access**
  Each vehicle is assigned a unique QR code linked to its ID

* 📲 **Instant WhatsApp Alerts**
  Sends pre-filled messages like:

  * Blocking vehicle
  * Emergency
  * Lights ON
  * Wrong parking

* 🔒 **Privacy-Aware Design**
  Phone numbers are stored securely in the database and not displayed on the UI

* ☁️ **Firebase Integration**
  Used Firestore for storing vehicle data

* 🧾 **Vehicle Registration System**
  Users can register their vehicle and generate QR codes

* 📊 **Dashboard (Optional Feature)**
  View alert history for a vehicle

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend (BaaS):** Firebase Firestore
* **Hosting:** GitHub Pages
* **Integration:** WhatsApp Click-to-Chat API

---

## 🔄 How It Works

1. User registers vehicle → gets QR code
2. QR code is placed on vehicle
3. Another user scans QR
4. Website opens with vehicle ID
5. User selects alert type
6. WhatsApp opens with pre-filled message
7. Owner receives alert instantly

---

## 🌐 Live Demo

👉 https://avneetkaur77.github.io/vehicle-alert/

---

## ⚙️ Setup Instructions

1. Clone the repository

```bash
git clone https://github.com/avneetkaur77/vehicle-alert.git
```

2. Open project folder
3. Run using Live Server OR open `index.html`

---

## 📸 Screenshots

(Add screenshots here if you want for better impact)

---

## ⚠️ Limitations

* Relies on WhatsApp redirection for alerts
* Phone number is visible inside WhatsApp chat (not on UI)
* No push notifications yet

---

## 🚀 Future Improvements

* 📱 Mobile app version (React Native)
* 🔔 Push notifications using Firebase Cloud Messaging
* 🔐 Secure backend for fully private messaging
* 📍 Location-based alerts
* 🚫 Spam protection system

---

## 💡 Inspiration

This project is inspired by common real-life parking issues where people struggle to contact vehicle owners quickly.

---

## 👩‍💻 Author

**Avneet Kaur**
GitHub: https://github.com/avneetkaur77

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
