# 🚀 Streamify – Real-Time Communication Platform

Streamify is a modern **real-time chat and calling platform** built with the **MERN stack**.
It enables users to connect with friends, send messages, manage friend requests, and make real-time calls in a clean and responsive interface.

The project demonstrates **full-stack architecture, authentication systems, real-time communication, and scalable UI patterns.**

---

# ✨ Features

### 👤 Authentication

* Secure user signup and login
* Password hashing using **bcrypt**
* JWT-based authentication
* Protected routes

### 👥 Social Layer

* Send friend requests
* Accept or reject requests
* View friends list
* User discovery

### 💬 Real-Time Chat

* One-to-one messaging
* Chat interface with conversation history
* Responsive chat UI

### 📞 Calling

* Real-time calling interface
* Dedicated call page

### 🔔 Notifications

* Friend request notifications
* Real-time updates

### 🎨 UI Experience

* Modern UI built with **React**
* Theme management using **Zustand**
* Toast notifications
* Loading states and skeleton screens

---

# 🏗️ Tech Stack

### Frontend

* React
* Vite
* React Router
* TanStack Query
* Zustand
* TailwindCSS
* React Hot Toast

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

### Dev Tools

* Git & GitHub
* ESLint
* Postman

---

# 🧠 Architecture Overview

```
streamify
│
├── frontend
│   ├── pages
│   ├── components
│   ├── store
│   ├── hooks
│   └── App.jsx
│
├── backend
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middleware
│   └── server.js
│
└── database
    └── MongoDB
```

---

# ⚡ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/streamify.git
cd streamify
```

---

### 2️⃣ Install backend dependencies

```bash
npm install
```

---

### 3️⃣ Install frontend dependencies

```bash
cd frontend
npm install
```

---

### 4️⃣ Environment Variables

Create `.env` in the backend root.

```
PORT=3000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

### 5️⃣ Run the project

Start backend:

```bash
npm run dev
```

Start frontend:

```bash
cd frontend
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

# 📸 Screenshots

Add screenshots here once deployed.

Example:

```
/screenshots/login.png
/screenshots/chat.png
/screenshots/call.png
```

---

# 🚀 Future Improvements

* Group chat
* Video calls
* Message reactions
* File sharing
* Online presence indicators
* Push notifications

---

# 💡 What This Project Demonstrates

* Full-stack MERN development
* Authentication & authorization
* API design
* State management
* Real-time communication architecture
* Scalable React project structure

---

# 👨‍💻 Author

**Karthik K**

If you liked this project, feel free to ⭐ the repository.

---
