# 💬 WhizChat Connect – Full-Stack Real-Time Chat App (MERN + Socket.IO)

WhizChat Connect is a **full-stack real-time chat application** built using the **MERN stack**  
(**MongoDB, Express.js, React.js, Node.js**) with **Socket.IO** for instant messaging.  

It supports **secure authentication**, **real-time conversations**, **auto-generated avatars**, and a **responsive UI**, designed to demonstrate production-ready **full-stack, real-time communication** skills.

---

## 🚀 Key Features

- 🔐 **Authentication & Authorization**
  - Secure user registration & login using **JWT (JSON Web Tokens)**  
  - Password hashing with **bcrypt** for safe credential storage  

- ⚡ **Real-Time Messaging**
  - Instant, bi-directional communication using **Socket.IO (WebSockets)**  
  - Messages sent, received, and displayed **without page reloads**  
  - Live updates for active chats  

- 🧑‍🎨 **User Avatars with DiceBear**
  - Integration with **DiceBear Avatars API**  
  - Automatically generates unique profile avatars during registration  

- 🗂️ **Persistent Chat History**
  - All messages and users stored in **MongoDB** via **Mongoose**  
  - Users can retrieve past conversations anytime  

- 📱 **Responsive UI**
  - Built with **React.js** and **Tailwind CSS / Styled Components**  
  - Mobile-first, clean, and modern interface  

- 🧩 **Scalable Backend**
  - RESTful API built with **Express.js**  
  - Modular structure for easy scalability and maintenance  

- 🌐 **Deployment**
  - **Frontend:** Deployed on **Vercel**  
  - **Backend:** Deployed on **Render**  
  - Environment variables managed securely in deployment platforms  

---

## 🛠️ Tech Stack

**Frontend**
- React.js  
- Tailwind CSS / Styled Components  
- Axios  

**Backend**
- Node.js  
- Express.js  

**Database**
- MongoDB  
- Mongoose ORM  

**Real-Time Communication**
- Socket.IO (WebSockets)  

**Authentication & Security**
- JWT  
- bcrypt  

**Avatar Service**
- DiceBear Avatars API  

**DevOps & Tools**
- Vercel (Frontend Hosting)  
- Render (Backend Hosting)  
- Git & GitHub (Version Control)  

---

## 📁 Project Structure (Example)

```bash
whizchat-connect/
├── client/               # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── utils/
│   └── package.json
├── server/               # Node + Express backend
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── sockets/
│   └── package.json
├── README.md
└── package.json          # (optional root config)
