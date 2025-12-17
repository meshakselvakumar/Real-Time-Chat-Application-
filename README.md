# Fullstack Chat Application

A real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js) and Socket.io.

<img width="1919" height="895" alt="Screenshot 2025-12-17 222708" src="https://github.com/user-attachments/assets/502884b1-2c13-4742-b7ef-b957c91c7550" />



## 🚀 Tech Stack

### Frontend
- **React** (with Vite)
- **TailwindCSS** & **DaisyUI** for styling
- **Zustand** for state management
- **React Router DOM** for routing
- **Axios** for API requests
- **Socket.io-client** for real-time communication
- **React Hot Toast** for notifications
- **Lucide React** for icons

### Backend
- **Node.js** & **Express.js**
- **MongoDB** & **Mongoose**
- **Socket.io** for real-time features
- **JWT** (JSON Web Tokens) for authentication
- **Bcryptjs** for password hashing
- **Cloudinary** for image storage
- **Cookie Parser** for handling cookies

## ✨ Features

- 🔐 **Authentication**: Secure login and signup using JWT.
- 💬 **Real-time Chat**: Instant messaging powered by Socket.io.
- 🟢 **Online Status**: See who is currently online.
- 🖼️ **Image Sharing**: Upload and share images in chat (via Cloudinary).
- 🎨 **Modern UI**: Clean and responsive interface using TailwindCSS and DaisyUI.
- 🔔 **Notifications**: Real-time toast notifications.

## 🛠️ Installation and Setup

### Prerequisites
- Node.js installed
- MongoDB installed or a MongoDB Atlas URI
- Cloudinary account for image uploads

### 1. Clone the repository
```bash
git clone <repository-url>
cd fullstack-chat-app
```

### 2. Setup Backend

Navigate to the backend directory:
```bash
cd backend
```

Install dependencies:
```bash
npm install
```

Create a `.env` file in the `backend` directory and add the following variables:
```env
PORT=5001
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
NODE_ENV=development
```

Start the backend server:
```bash
npm run dev
```

### 3. Setup Frontend

Open a new terminal and navigate to the frontend directory:
```bash
cd frontend
```

Install dependencies:
```bash
npm install
```

Start the frontend development server:
```bash
npm run dev
```

## 📜 Scripts

### Root
- `npm run build`: Installs dependencies for both backend and frontend, and builds the frontend.
- `npm start`: Starts the backend server (production mode).

### Backend
- `npm run dev`: Starts the backend server with Nodemon (development).
- `npm start`: Starts the backend server (production).

### Frontend
- `npm run dev`: Starts the Vite development server.
- `npm run build`: Builds the app for production.
- `npm run preview`: Previews the production build.
- `npm run lint`: Runs ESLint.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## wc License

This project is licensed under the ISC License.

