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
## 📸 Screenshots

<div style="display: flex; gap: 10px; overflow-x: auto;">
  <img src="https://github.com/user-attachments/assets/312107f8-f177-4ac9-90ce-bfc6cebaba30" alt="Login" width="300">
  <img src="https://github.com/user-attachments/assets/f8e641bc-110e-4f70-a1a6-ed23b8cf55c7" alt="Admin Panel" width="300">
  <img src="https://github.com/user-attachments/assets/1938b864-224b-4a40-9eeb-d08b7f16d9c5" alt="Student Dashboard" width="300">
  <img src="https://github.com/user-attachments/assets/9b98eba4-646c-4413-a8b2-a4d9500b5dab" alt="Buy Course" width="300">
  <img src="https://github.com/user-attachments/assets/754e7625-58d4-4eb7-be08-407c252017c7" alt="Live Class" width="300">
  <img src="https://github.com/user-attachments/assets/1de9af6b-9415-4fc6-84ba-f31a7a1c232f" alt="Chat" width="300">
  <img src="https://github.com/user-attachments/assets/189dfc8c-1cb4-4360-a096-e4ee342ae9ee" alt="Course List" width="300">
</div>


## 📲 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Kalpesh-Sananse/dpsi-avishkar.git
