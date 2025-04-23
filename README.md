# 🚆 Railway Reservation System (MERN Stack)

A full-stack web application that allows users to search, book, and manage train tickets online. It includes a user-friendly frontend, a secure backend, booking system, and an admin portal for managing trains and schedules.

---

## 🧰 Tech Stack

### 🔹 Frontend (React + TypeScript + Vite)
- ReactJS
- Vite
- TypeScript
- Axios
- React Router

### 🔹 Backend (Express.js + MongoDB)
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Bcrypt for password hashing
- dotenv, cors, morgan

---

## ✨ Features

### 👥 User Module
- Register & Login with JWT Auth
- Search Trains by source/destination/date
- Book tickets in real-time
- View booking history
- PNR status check

### 🛠 Admin Module
- Add/Edit/Delete Trains
- Set train schedules and availability
- Manage all bookings

### 📱 Other
- Fully responsive UI
- Secure API routes
- Future-ready payment system

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/sruthisoppa/Railway-Reservation-System.git
cd Railway-Reservation-System
2. Backend Setup
bash
Copy
Edit
cd backend
npm install
npm run dev
Create a .env file inside backend/ with the following:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
3. Frontend Setup
bash
Copy
Edit
cd ../frontend
npm install
npm run dev
Make sure the frontend uses correct API URLs (proxy or env settings).

🧪 Folder Structure (Simplified)
bash
Copy
Edit
backend/
├── config/
├── controllers/
├── models/
├── routes/
└── server.js

frontend/
└── src/
    ├── components/
    ├── pages/
    ├── hooks/
    ├── utils/
    ├── App.tsx
    └── main.tsx
💡 Future Enhancements
Payment gateway integration (e.g., Razorpay/Stripe)

SMS/email ticket confirmations

Admin analytics dashboard

PNR sharing via WhatsApp/email
