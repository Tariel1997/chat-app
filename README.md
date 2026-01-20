# 🗨️ Chat App

A full-stack real-time chat application built with the **MERN** stack (MongoDB, Express, React, Node.js). This application enables users to send text messages and images in real-time.

## 🚀 Features

- 💬 **Real-time Messaging**: Instant delivery of messages using **Socket.io**.
- 🔐 **User Authentication**: Secure signup and login with **JWT** and **Bcrypt**.
- 🖼️ **Image Sharing**: Upload and send images via **Cloudinary**.
- 🟢 **Online Status**: Real-time online user status updates.
- 📱 **Responsive UI**: Built with **TailwindCSS** and **DaisyUI** for a modern, mobile-friendly design.
- 🐻 **State Management**: Scalable frontend state management using **Zustand**.
- 🔔 **Toasts & Notifications**: Interactive feedback with **React Hot Toast**.
- ⚠️ **Error Handling**: Comprehensive error handling on both client and server.

## 🛠️ Tech Stack

### 🖥️ Frontend
- **React** (Vite) ⚛️
- **TailwindCSS** 🎨 & **DaisyUI** 🌼
- **Zustand** (State Management) 🐻
- **Axios** 📡
- **React Router DOM** 🗺️
- **Socket.io Client** 🔌
- **Lucide React** (Icons) 🖌️

### ⚙️ Backend
- **Node.js** 🟢
- **Express.js** 🚂
- **MongoDB** (Mongoose) 🍃
- **Socket.io** 🔌
- **JsonWebToken** (JWT) 🔑
- **Bcrypt.js** 🛡️
- **Cloudinary** ☁️
- **Cookie Parser** 🍪

## 📦 Setup & Installation

Follow these steps to get the project running locally.

### 📥 1. Clone the repository
```bash
git clone https://github.com/Tariel1997/chat-app.git
cd chat-app
```

### 💿 2. Install Dependencies

You need to install dependencies for both the backend and frontend.

**Backend:**
```bash
cd backend
npm install
```

**Frontend:**
```bash
cd ../frontend
npm install
```

### 🔑 3. Environment Configuration

Create a `.env` file in the `backend` directory and add the following variables:

```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
NODE_ENV=development
```

### ▶️ 4. Run the Application

You will need to run the backend and frontend in separate terminals.

**Start Backend:**
```bash
cd backend
npm run dev
```

**Start Frontend:**
```bash
cd frontend
npm run dev
```

## 📜 Available Scripts

### Root
- `npm start`: Starts the backend server.
- `npm run build`: Installs dependencies for both ends and builds the frontend.

### Backend
- `npm run dev`: Starts the backend in development mode with Nodemon.
- `npm start`: Starts the backend in production mode.

### Frontend
- `npm run dev`: Starts the frontend development server.
- `npm run build`: Builds the frontend for production.
- `npm run preview`: Previews the production build.
