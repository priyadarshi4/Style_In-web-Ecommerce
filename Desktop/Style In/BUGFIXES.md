# Style In 🛍️  
### A Modern Full-Stack eCommerce Startup Platform

**Style In** is a full-stack eCommerce web application built to deliver a fast, secure, and visually engaging online shopping experience.  
The platform is designed with **startup scalability**, **real-world business workflows**, and **modern UI/UX standards** in mind.

Style In is not just a demo project — it is architected like a **production-ready startup application**.

---

## 🌟 Introduction

Style In aims to redefine online shopping by combining:
- Clean and modern design
- Smooth user experience
- Secure backend architecture
- Scalable codebase

The platform supports both **customers** and **administrators**, making it suitable for real eCommerce businesses.

---

## 🎯 Vision & Mission

### Vision
To build a scalable, user-friendly eCommerce ecosystem that can grow into a full digital commerce brand.

### Mission
- Provide a smooth and intuitive shopping experience
- Maintain secure and reliable backend systems
- Design a platform that can scale with business growth
- Follow clean coding and industry best practices

---

## 👥 User Roles

### 👤 Customer
- Browse products
- Manage cart
- Place orders
- Track order history
- Manage personal profile

### 🛠️ Admin
- Manage products
- Control inventory
- View and manage orders
- Manage users
- Oversee platform operations

---

## ✨ Core Features (Detailed)

### 🔐 Authentication & Security
- User registration and login
- JWT-based authentication
- Secure password hashing
- Email verification
- Forgot & reset password via email
- Protected routes (user/admin)

---

### 🛒 Product Management
- Product listing with images
- Product details page
- Category-based organization
- Price, stock, and description management
- Cloud image storage support

---

### 🧺 Cart System
- Add to cart
- Remove from cart
- Quantity updates
- Persistent cart using state management
- Price calculation in real time

---

### 💳 Order & Checkout
- Shipping information handling
- Order summary before payment
- Secure payment flow
- Order confirmation
- Order status tracking

---

### 📦 Order Management
- User order history
- Order detail view
- Admin order control
- Order status updates (Processing / Shipped / Delivered)

---

### 🧑‍💼 Admin Dashboard
- Admin-only access
- Product creation, update, deletion
- User management
- Order management
- Inventory monitoring

---

### 🎨 UI / UX Experience
- Fully responsive layout
- Mobile-first design
- Smooth animations and transitions
- Clean typography and color scheme
- Optimized user navigation

---

## 🏗️ Tech Stack (In Depth)

### Frontend
- **React.js** – Component-based UI
- **Redux Toolkit** – Global state management
- **Axios** – API communication
- **CSS / Custom Styling** – Modern responsive UI

### Backend
- **Node.js** – Server runtime
- **Express.js** – Backend framework
- **MongoDB** – NoSQL database
- **Mongoose** – Schema & model handling
- **JWT** – Authentication & authorization
- **Nodemailer** – Email services

### Database
- **MongoDB Atlas**
- Structured schemas for users, products, orders, and payments

### DevOps & Tools
- Git & GitHub
- Environment-based configuration
- RESTful API architecture
- Modular code structure

---

## 📂 Project Structure (Explained)

Style-In/
│
├── backend/
│ ├── controllers/ # Business logic
│ ├── models/ # Database schemas
│ ├── routes/ # API routes
│ ├── middleware/ # Auth & error handling
│ ├── utils/ # Helper utilities
│ └── app.js # Express app entry
│
├── frontend/
│ ├── public/ # Static assets
│ ├── src/
│ │ ├── components/ # UI components
│ │ ├── actions/ # Redux actions
│ │ ├── reducers/ # Redux reducers
│ │ ├── constants/ # App constants
│ │ ├── utils/ # Helper functions
│ │ └── store.js # Redux store
│ └── package.json
│
├── .gitignore
├── package.json
└── README.md
