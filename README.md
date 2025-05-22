# NexaChat - Real-Time Chat Application

NexaChat is a fully responsive, scalable, and secure one-on-one chat application built using the MERN stack and Socket.IO for seamless real-time communication.

---

## 🔑 Features

- **Real-Time Messaging**  
  Instant delivery of messages powered by Socket.IO and WebSocket protocol.

- **Secure Authentication**  
  Robust login/signup system using JWT and bcrypt.js ensuring secure user sessions.

- **Profile Management**  
  Edit user details and upload avatars via Cloudinary.

- **User Preferences**  
  Clean settings interface to personalize the chat experience.

- **Mobile-First Design**  
  Fully responsive across mobile, tablet, and desktop devices.

- **Optimized Backend**  
  Efficient MongoDB data models for storing user profiles and chat logs with high availability.

---

## 🛠️ Tech Stack

### Frontend

- React 19 with Vite  
- React Router v7  
- Tailwind CSS + DaisyUI for modern UI components  
- Zustand for state management  
- Socket.IO Client for real-time communication  

### Backend

- Node.js with Express  
- MongoDB with Mongoose  
- Socket.IO for real-time server communication  
- JWT for token-based authentication  
- Cloudinary for image uploads  
- bcrypt.js for secure password hashing  

---

## ⚙️ Getting Started

### Prerequisites

- Node.js (v18+)
- MongoDB Atlas account
- Cloudinary account for image storage

---

## 🧩 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/NexaChat.git
cd NexaChat
```

### 2. Setup the Backend

```bash
cd backend
npm install
```
Create a .env file in the backend/ directory with the following variables:

```bash
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```
Start the backend server:
```bash
npm run dev
```
### 3. Setup the Frontend
 ```bash
cd ../frontend
npm install
npm run dev
```

---

## 🗂️ Project Structure
```bash
NexaChat/
├── backend/
│   ├── src/
│   │   ├── controllers/    # API logic
│   │   ├── models/         # Mongoose schemas
│   │   ├── routes/         # Express routes
│   │   ├── middleware/     # Auth & error handling
│   │   ├── lib/            # Utils/configs
│   │   └── index.js        # Entry point
│   └── package.json
│
└── frontend/
    ├── src/
    │   ├── components/     # UI components
    │   ├── pages/          # Main screens
    │   ├── store/          # Zustand state
    │   ├── lib/            # Utilities & config
    │   └── App.jsx         # App root
    └── package.json
```

---

## ✨ Acknowledgements

This project was developed as part of a deep dive into full-stack development using the MERN stack and WebSocket-based communication.
Special thanks to the open-source community for providing incredible tools and documentation.






