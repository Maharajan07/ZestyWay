# ZestyWay – Food Ordering WebApp

A full-stack MERN application designed to deliver a smooth and efficient food ordering experience. ZestyWay includes both User and Admin panels with secure authentication, payment integration, and complete order management.

🔗 **Live Demo:** [Visit Site](https://zestyway-1.onrender.com)

---

## ✨ Features

### 🧑‍🍳 User Panel

- Sign Up / Login / Logout  
- Browse & Filter Food Items  
- Add to Cart  
- Place Orders  
- Stripe Payment Integration  
- View Past Orders  

### 🔐 Admin Panel

- Secure Admin Login  
- Manage Products (CRUD)  
- Order Tracking & Management  
- Role-Based Access Control  

### 🛡 Authentication & Security

- JWT Authentication  
- Password Hashing with Bcrypt  
- Protected Routes & Authenticated APIs  

### 💳 Payments

- Stripe Payment Gateway Integration  

---

## 🚀 Run Locally

### 1️⃣ Clone the Project

```bash
git clone https://github.com/Maharajan07/ZestyWay
cd Food-Delivery
```
### 2️⃣ Install Dependencies
```bash
cd frontend
npm install

cd ../admin
npm install

cd ../backend
npm install
```
### 3️⃣ Set Up Environment Variables
In the backend folder, create a .env file with the following:

```bash
JWT_SECRET=your_jwt_secret
SALT=your_salt_value
MONGO_URL=your_mongo_db_url
STRIPE_SECRET_KEY=your_stripe_test_key
```

### 4️⃣ Update URLs
In Admin Panel → App.jsx:

```bash
const url = "your_backend_url";
```

In Frontend → StoreContext.js:

```bash
const url = "your_backend_url";
```

In Backend → orderController.js:

```bash
const frontend_url = "your_frontend_url";
```

### 5️⃣ Start Development Servers
Backend:

```bash
cd backend
nodemon server.js
```

Frontend:

```bash
cd frontend
npm start
```

Admin:

```bash
cd admin
npm start
```

## 🛠 Tech Stack
Frontend: React, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Authentication: JWT, Bcrypt

Payments: Stripe

---

#### Made by Maharajan
