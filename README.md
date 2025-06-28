# Real-Time Chat Application with MERN Stack

## Project Description

This project is a **real-time chat application** built using the **MERN stack** (MongoDB, Express, React, and Node.js), with the integration of **Socket.io** for real-time messaging. The app allows users to sign up, log in, update their profiles, and engage in real-time communication.

### Key Features:
- **Real-time Messaging**: Users can send and receive messages instantly, thanks to the integration of **Socket.io**.
- **Authentication & Authorization**: Secure user signup, login, and profile management using **JWT** (JSON Web Tokens).
- **Profile Management**: Users can update their profile information.
- **Responsive UI**: Built with **React**, the frontend ensures a smooth, responsive user interface that works across devices.


## Highlights:
- Tech stack: MERN + Socket.io 
- Authentication & Authorization with JWT
- Real-time messaging with Socket.io
- Online user status
- Global state management with Zustand
- Error handling both on the server and on the client

## Setup .env file
```bash
MONGODB_URI="mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority"
PORT=5001
JWT_SECRET="<your-secret-key>"
CLOUDINARY_CLOUD_NAME="<your-cloudinary-cloud-name>"
CLOUDINARY_API_KEY="<your-cloudinary-api-key>"
CLOUDINARY_API_SECRET="<your-cloudinary-api-secret>"
NODE_ENV="development"
```

## Run the app
## Backend
```bash
cd backend
npm i
npm run dev
```
## Frontend
```bash
cd frontend
npm i
npm run dev
