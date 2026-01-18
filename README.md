# Full Stack Realtime Chat App

A modern **full-stack realtime chat application** built with the **MERN stack**, featuring instant messaging powered by **Socket.io**, a clean UI using **TailwindCSS + DaisyUI**, and secure authentication with **JWT**.

🌐 **Live Demo:**  
https://fullstack-chat-app-hmgt.onrender.com

---

## 🚀 Highlights

- **Tech Stack:** MERN (MongoDB, Express, React, Node.js)
- **Realtime Messaging:** Socket.io
- **Authentication & Authorization:** JWT
- **Online User Status** indicator
- **Global State Management:** Zustand
- **Image Uploads:** Cloudinary
- **Modern UI:** TailwindCSS + DaisyUI
- **Robust Error Handling** (Server & Client)
- **Production-ready setup**

---

## ⚙️ Environment Variables Setup

Create a `.env` file in the root directory and add the following:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### 🛠️ Installation & Setup
### 1️⃣ Clone the Repository
```
git clone https://github.com/your-username/fullstack-chat-app.git
cd fullstack-chat-app
```
### 2️⃣ Install Dependencies
```
npm install
```
### 3️⃣ Build the Application
```
npm run build
```
### 4️⃣ Start the Application
```
npm start
```
### The application will run on:
```
http://localhost:5001
```
### 📈 How It Works
```
Users authenticate using JWT-based login and registration.
Realtime Communication : Socket.io enables instant message delivery and live user status.
State Management : Zustand manages global application state efficiently.
Media Handling : Cloudinary handles image uploads within chats.
```
### 📝 Usage
```
Register or log in to start chatting.
Send real-time messages with online status updates.
Upload images securely using Cloudinary.
Experience seamless UI with responsive design.
```
### 💡 Future Enhancements
```
Group chats
Message reactions & read receipts
Voice and video calling
Push notifications
Chat search and message history
```
