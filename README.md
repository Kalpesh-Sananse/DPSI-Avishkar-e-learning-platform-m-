# 📚 DPSI Avishkar - E-Learning Platform for Forensic Education

[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/)
[![Made with Kotlin](https://img.shields.io/badge/Made%20with-Kotlin-blueviolet)](https://kotlinlang.org/)
[![Firebase](https://img.shields.io/badge/Backend-Firebase-orange)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**DPSI Avishkar** is a mobile-first, full-featured e-learning platform tailored for forensic institutes. It includes admin, teacher, and student portals, allowing content management, digital sales, and seamless online learning experiences — from daily live lectures to recorded sessions, chat, and secure payments.

---

## 🚀 Features

### 🔐 Authentication
- Firebase Authentication (Email & Password)
- Role-based login system:
  - **Admin**
  - **Teacher**
  - **Student**

### 🧑‍💼 Admin Panel
- Add, edit, and delete:
  - Courses
  - Notes
  - Live and recorded lectures
- Upload content using Firebase Storage
- Monitor and manage all users
- Sell digital content (courses, notes)

### 🧑‍🏫 Teacher Dashboard
- Upload study material and lecture videos
- Conduct daily **live classes**
- Chat with students for doubt resolution

### 👨‍🎓 Student Portal
- Browse and **purchase** courses and notes
- Access **live** and **recorded** lectures
- **Chat with teachers** in real time
- Track purchased content
- View learning history

### 💳 Payment Gateway
- Integrated **Razorpay** for secure payments
- Firebase stores transaction details

---

## 🛠️ Tech Stack

| Layer        | Technology                    |
|--------------|-------------------------------|
| **Frontend** | Kotlin (Android Native)        |
| **Backend**  | Firebase (Auth, Firestore, Storage, Realtime DB) |
| **Payment**  | Razorpay Gateway               |
| **Live Class** | Embedded streaming (Jitsi/Zoom) |
| **Chat**     | Firebase Realtime DB or Firestore |

---

## 📲 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kalpesh-Sananse/dpsi-avishkar.git
