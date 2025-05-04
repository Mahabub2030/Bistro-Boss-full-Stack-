# Bistro-Boss-full-Stack-

A modern, full-stack restaurant management and user interaction web application built with the MERN stack and styled using Tailwind CSS and DaisyUI. Authentication is handled securely using Firebase and JWT tokens.

---

## 🔥 Live Demo

[👉 Click here to view the live app](#) *(Replace with your live deployment link)*

---

## 🛠️ Tech Stack

### 🧩 Frontend:
- React.js
- Tailwind CSS
- DaisyUI

### 🔧 Backend:
- Node.js
- Express.js
- MongoDB

### 🔐 Authentication:
- Firebase Authentication
- JSON Web Token (JWT)

---

## ✨ Features

- 🔐 **Secure Login & Registration** using Firebase and JWT
- 📋 **User Roles & Permissions** (Admin & User)
- 🛒 **Order Management System**
- 📦 **Menu Management** (CRUD operations)
- 🧾 **Real-Time Cart & Checkout**
- 📊 **Admin Dashboard** with analytics
- 💬 **Customer Feedback System**
- 📱 Fully Responsive Design with Tailwind CSS and DaisyUI

---

## 🔐 Authentication Flow

1. User logs in or registers via Firebase Authentication.
2. Firebase issues an ID Token.
3. The frontend sends the token to the backend.
4. The backend verifies the token and issues a secure JWT for session validation.
5. Protected routes are only accessible with a valid JWT.

---

## 📁 Project Structure

