# 💬 Realtime Chat Application (MERN + Socket.io)

A full-stack **Realtime Chat App** built using the **MERN stack** (MongoDB, Express, React, Node.js) with **Socket.io** for instant messaging.  
This project includes authentication, real-time messaging, online status, and profile management.

---

## 🚀 Features

- 🔐 User authentication (JWT based)
- 💬 Real-time messaging with Socket.io
- 🟢 Online/offline user status
- 👤 Profile update (avatar, name, etc.)
- 📂 MongoDB message & user storage
- ⚡ Global state management (Zustand)
- 📱 Responsive UI (TailwindCSS / DaisyUI)
- 🌐 Full-stack MERN architecture

---

## 🛠️ Tech Stack

**Frontend**
- React.js
- TailwindCSS
- DaisyUI
- Zustand
- Axios
- Socket.io-client

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.io
- JWT Authentication
- bcrypt

---

## 📁 Folder Structure
Chat-Application/
│
├── frontend/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── store/
│ │ ├── utils/
│ │ └── App.jsx
│ └── package.json
│
├── backend/ # Node backend
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── middleware/
│ ├── socket/
│ └── server.js
│
├── .env
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

- git clone https://github.com/Agarwalsonali/Chat_Application.git

- cd Chat_Application


### 2️⃣ Backend Setup

- cd backend
- npm install

- MONGO_URI=your_mongodb_uri
- JWT_SECRET=your_secret_key

- npm run dev


### 3️⃣ Frontend Setup

- cd frontend
- npm install

- VITE_API_URL=your_backend_url

- npm run dev



---

### 🧪 How to Use

- Register a new account
- Login
- Open chat
- Send messages in real time


---

### 🔌 Socket.io Events

| Event            | Description     |
| ---------------- | --------------- |
| `connection`     | User connects   |
| `sendMessage`    | Send message    |
| `receiveMessage` | Receive message |
| `disconnect`     | User leaves     |



---

### 📚 Learning Goals

- This project helps understand:
- MERN stack integration
- Real-time communication
- Authentication with JWT
- Global state management