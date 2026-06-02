# 🎥 Apna Video Call

A Full Stack Video Conferencing Application built with **MERN Stack, WebRTC, Socket.IO, and MongoDB Atlas**. This platform enables users to create and join video meetings, communicate through real-time chat, share screens, and collaborate seamlessly from anywhere.

---

## 🚀 Live Demo
https://apnacollagezoomfrontend-vova.onrender.com

### Frontend

Deployed on Render

### Backend API

Deployed on Render

---

## ✨ Features

### 🔐 Authentication

* User Registration
* User Login
* JWT Authentication
* Secure User Sessions

### 🎥 Video Conferencing

* One-to-One Video Calling
* Multi-User Video Meetings
* Real-Time Audio & Video Streaming
* WebRTC Peer-to-Peer Communication

### 💬 Real-Time Chat

* Instant Messaging During Meetings
* Live Message Broadcasting
* Meeting-Specific Chat Rooms

### 🖥️ Screen Sharing

* Share Entire Screen
* Presentation Friendly
* Real-Time Screen Stream

### 🎙️ Media Controls

* Mute / Unmute Microphone
* Turn Camera On / Off
* End Meeting Functionality

### 📋 Meeting Management

* Create New Meeting
* Join Existing Meeting
* Store Meeting History
* Meeting Records in MongoDB

### 📱 Responsive Design

* Desktop Friendly
* Mobile Friendly
* Modern UI Experience

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Material UI
* Socket.IO Client
* WebRTC
* Axios
* React Router DOM

### Backend

* Node.js
* Express.js
* Socket.IO
* JWT
* Bcrypt

### Database

* MongoDB Atlas
* Mongoose

### Deployment

* Render (Frontend)
* Render (Backend)

---

## 📂 Project Structure

```bash
Apna-Video-Call
│
├── Frontend
│   ├── public
│   ├── src
│   │   ├── pages
│   │   ├── context
│   │   ├── styles
│   │   ├── utils
│   │   └── environment.js
│   └── package.json
│
├── Backend
│   ├── src
│   │   ├── controllers
│   │   ├── models
│   │   ├── routes
│   │   ├── middleware
│   │   └── app.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/kuna1900/Apna-Video-Call.git
cd Apna-Video-Call
```

---

## Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Start Backend:

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd Frontend
npm install
npm start
```

---

## 🌐 Environment Configuration

### Frontend

```javascript
let IS_PROD = true;

const server = IS_PROD
  ? "https://your-backend-url.onrender.com"
  : "http://localhost:8000";

export default server;
```

---

## 🔄 Application Workflow

1. User logs into the platform.
2. User creates or joins a meeting room.
3. Socket.IO establishes signaling communication.
4. WebRTC creates peer-to-peer connections.
5. Audio and video streams are exchanged.
6. Users can send chat messages in real time.
7. Screen sharing can be enabled during meetings.
8. Meeting information is stored in MongoDB.

---

## 🔌 API Endpoints

### Authentication

```http
POST /api/v1/users/register
POST /api/v1/users/login
```

### Meetings

```http
POST /api/v1/users/add_to_activity
GET  /api/v1/users/get_all_activity
```

---

## 📸 Screenshots

### Login Page

* User Authentication Interface

### Dashboard

* Meeting Creation & History

### Video Meeting Room

* Video Calling
* Screen Sharing
* Real-Time Chat
* Audio/Video Controls

---

## 🚀 Deployment

### Frontend

* Render Static Site

### Backend

* Render Web Service

### Database

* MongoDB Atlas

---

## 🔒 Security Features

* Password Hashing using Bcrypt
* JWT Authentication
* Protected Routes
* Secure API Communication

---

## 🎯 Future Improvements

* Meeting Recording
* File Sharing
* Raise Hand Feature
* Waiting Room
* Meeting Scheduling
* Live Captions
* AI Meeting Notes
* Virtual Backgrounds

---

## 👨‍💻 Author

### Kunal Choudhary

* GitHub: https://github.com/kuna1900
* LinkedIn: https://www.linkedin.com](https://www.linkedin.com/in/kunal-choudhary-b19a62247/

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

### Made with ❤️ using MERN Stack, WebRTC, Socket.IO and MongoDB Atlas
