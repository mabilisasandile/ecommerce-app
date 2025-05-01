# 👕 Clothing E-Commerce App

A full-stack clothing e-commerce platform built with **React**, **Tailwind CSS**, **Node.js**, **MongoDB**, and **Cloudinary**. This app allows users to browse, search, and purchase clothing, while admins can manage inventory, orders, and product uploads.

---

## 📑 Table of Contents

- [Tech Stack](#-tech-stack)
- [Features](#-features)
- [System Architecture](#-system-architecture)
- [Frontend](#-frontend)
- [Backend](#-backend)
- [Database](#-database)
- [Media Management](#-media-management)
- [Authentication](#-authentication)
- [Installation & Setup](#-installation--setup)
- [Environment Variables](#-environment-variables)
- [API Endpoints](#-api-endpoints)
- [Deployment](#-deployment)
- [Contributing](#-contributing)

---

## 🛠️ Tech Stack

- **Frontend:** React, Tailwind CSS, React Router, Axios
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (via Mongoose)
- **Media Storage:** Cloudinary
- **Authentication:** JWT

---

## 🎯 Features

### 🧑 User

- Register/Login
- Browse clothing by category
- Add to cart
- Place orders & track order history

### 🛒 Admin

- Add, edit, delete products
- Upload product images
- Manage customer orders
- View user data

---

## 🏗️ System Architecture

---

## 🎨 Frontend

- Built with React and styled using Tailwind CSS
- Routes managed with React Router
- API interaction via Axios
- Responsive UI with product cards, modals, and dashboards

### Pages

- Home
- Products List
- Product Details
- Cart
- Checkout
- Login/Register
- User Dashboard
- Admin Dashboard

---

## 🧮 Backend

- RESTful API with Express.js
- Middleware for authentication & authorization
- Routes for users, products, and orders
- File uploads handled via Cloudinary SDK

---

## 🗃️ Database

### Collections

- `users`: User credentials & roles
- `products`: Item details, price, category, image URL, stock
- `orders`: User orders, order status
- `categories`: Product categories

---

## ☁️ Media Management (Cloudinary)

- Images uploaded by admin via the dashboard
- Stored in Cloudinary with public URLs saved in MongoDB
- Cloudinary SDK used in backend for handling uploads

---

## 🔐 Authentication

- JWT used for secure authentication
- Token issued on login and used for protected routes
- Role-based access control for admin vs. regular users

---

## 🧰 Installation & Setup

### Prerequisites

- Node.js and npm
- MongoDB (Atlas or local)
- Cloudinary account

### Backend

```bash or terminal
cd server
npm install
npm run dev


### Frontend

```bash or terminal
cd client
npm install
npm start

🌐 Environment Variables

VITE_BACKEND_URL = "https://ecommerce-app-zgmy.onrender.com"
MONGODB_URI = "mongodb+srv://mabilisasandile:Sjmabilisa93@cluster0.7wl9s.mongodb.net"
CLOUDINARY_API_KEY = "646274181128426"
CLOUDINARY_SECRET_KEY = "F6J1W2Pv89N0Lj394HF21s0qzB0"
CLOUDINARY_NAME = "dccsxcslg"
JWT_SECRET = "samabstack"
ADMIN_EMAIL = "admin.sandile@outlook.com"
ADMIN_PASSWORD = "Sandile@Admin123"
STRIPE_SECRET_KEY = "sk_test_51O0LfwH0Oo7ShsJ8CiYi8iOcRrUFbZkFWtFs0vg8vyDZYQu8yWP886LXTh5bBhLAUxGCJQrRLbIhHCXsd9HVsU1i00Aa15c6A1"

📡 API Endpoints
Auth
POST /api/auth/register – Register a new user
POST /api/auth/login – Login
GET /api/auth/profile – Get user profile

Products
GET /api/products – Get all products
GET /api/products/:id – Get product by ID
POST /api/products – Add product (Admin)
PUT /api/products/:id – Update product (Admin)
DELETE /api/products/:id – Delete product (Admin)

Orders
POST /api/orders – Create order
GET /api/orders/:userId – Get user orders
PUT /api/orders/:orderId – Update order status (Admin)

🚀 Deployment
Frontend: Deployed with Netlify
Backend: Deployed with Render

🤝 Contributing
Fork the repository
Create a new branch: git checkout -b feature/your-feature
Commit your changes: git commit -m 'Add your feature'
Push to the branch: git push origin feature/your-feature
Submit a pull request

Following are the Links that can be used to explore this app:

Backend URLs:
LIVE LINK - https://ecommerce-app-zgmy.onrender.com
GITHUB LINK - https://github.com/mabilisasandile/ecommerce-app/tree/backend

Frontend URLs:
GITHUB LINK - https://github.com/mabilisasandile/ecommerce-app/tree/main
LIVE LINK - https://abx-ecommerce.netlify.app

Admin URLs & Login Credentials:
GITHUB LINK - https://github.com/mabilisasandile/admin-ecommerce-app
LIVE LINK - https://admin-abx-ecommerce.netlify.app
Username: admin.sandile@outlook.com

📧 Contact
For any inquiries or feedback, feel free to send a message or call:
Email: Mabilisasandile@gmail.com
Phone: +2773 4908 931
Password: Sandile@Admin123
