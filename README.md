# 💬 Real-Time Chat Application (React + Firebase)

A real-time chat application built using React and Firebase, featuring Google Authentication and live message updates using Cloud Firestore.

This project demonstrates authentication flow, real-time database integration, and modern frontend architecture.

---

## 📌 Project Overview

This application allows users to:

- Sign in using Google Authentication
- Send and receive messages instantly
- View live chat updates without refreshing
- Maintain secure authenticated sessions
- Store and sync messages using Firestore

The project was built to explore real-time systems and cloud-based authentication using Firebase.

---

## 🛠 Tech Stack

Frontend:
- React.js (Create React App)
- JavaScript (ES6+)
- CSS

Cloud Services:
- Firebase Authentication (Google OAuth)
- Cloud Firestore (Real-Time Database)

---

## 🔐 Authentication

Authentication is handled using:

- Firebase Google Sign-In
- Secure OAuth flow
- Firebase-managed session handling

Firebase Auth is initialized inside:


src/config/Firebase.js


---

## ⚡ Real-Time Messaging

Messages are stored and synced using:

- Cloud Firestore
- Real-time listeners (`onSnapshot`)
- Automatic UI updates on data changes

---

## 📂 Project Structure


chatapp/
│
├── public/
├── src/
│ ├── components/ # Reusable UI components
│ ├── config/ # Firebase configuration
│ │ └── Firebase.js
│ ├── styles/ # CSS styles
│ ├── App.js
│ ├── App.css
│ ├── index.js
│ └── ...
│
├── package.json
└── README.md


---

## 🚀 Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/sajar-mohammed/chatapp.git
cd chatapp
2️⃣ Install Dependencies
npm install
3️⃣ Firebase Configuration

Create a .env file in the root directory:

REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id

⚠️ Important: Do not commit Firebase credentials to GitHub.

4️⃣ Start Development Server
npm start

Open:

http://localhost:3000
🎯 Features

Google OAuth login

Real-time message updates

Firestore-based data storage

Component-based architecture

Clean and modular structure

🧠 What I Learned

Implementing OAuth authentication

Managing real-time data with Firestore

Handling async state updates in React

Structuring scalable frontend applications

Securing frontend applications using Firebase rules

🔮 Future Improvements

Add chat rooms

Add private messaging

Add typing indicators

Deploy to Firebase Hosting

Improve UI/UX responsiveness

Add message timestamps formatting

👨‍💻 Author

Sajar Mohammed
GitHub: https://github.com/sajar-mohammed
