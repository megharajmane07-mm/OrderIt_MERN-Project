# 🍔 OrderIt – Full Stack MERN Food Ordering Platform

<div align="center">

# 🍽️ OrderIt

### A Modern Full Stack Food Ordering Platform Built with the MERN Stack

Order Food • Secure Payments • Live Order Tracking • Admin Dashboard • AI-Powered Menu Management

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-20-339933?style=for-the-badge&logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-Backend-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb)
![Stripe](https://img.shields.io/badge/Stripe-Payments-635BFF?style=for-the-badge&logo=stripe)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange?style=for-the-badge)
![Grok AI](https://img.shields.io/badge/Grok-AI-blue?style=for-the-badge)
![Postman](https://img.shields.io/badge/Postman-API_Testing-FF6C37?style=for-the-badge&logo=postman)

### 🚀 Full Stack MERN Application with Secure Authentication, Stripe Payments & AI Integration

</div>

---

# 📖 About the Project

**OrderIt** is a feature-rich **Full Stack MERN Food Ordering Platform** developed using **MongoDB, Express.js, React.js, and Node.js**.

The application provides customers with a seamless food ordering experience—from browsing restaurants and menus to placing secure online orders using **Stripe Payment Gateway**.

A dedicated **Admin Dashboard** enables efficient management of restaurants, menus, and food items. To further enhance productivity, **Grok AI** is integrated to automatically generate attractive dish descriptions.

This project demonstrates real-world implementation of:

- Full Stack MERN Development
- REST API Development
- Authentication & Authorization
- Payment Gateway Integration
- AI Integration
- CRUD Operations
- Secure Backend Development
- Responsive Frontend Design

---

# ✨ Features

## 👤 User Features

- Secure User Registration
- User Login & Logout
- JWT Authentication
- Browse Restaurants
- Explore Restaurant Menus
- Add Items to Cart
- Update Cart Quantity
- Remove Cart Items
- Place Orders
- View Previous Orders
- Live Order Tracking
- Fully Responsive UI

---

## 💳 Payment Features

- Stripe Payment Gateway
- Secure Checkout
- Payment Verification
- Order Confirmation
- Real-Time Order Updates

---

## 👨‍💼 Admin Features

- Secure Admin Login
- Restaurant Management
- Add Restaurants
- Delete Restaurants
- Menu Management
- Add Food Items
- Delete Food Items
- Manage Customer Orders
- Dashboard Controls

---

## 🤖 AI Features

- Grok AI Integration
- AI Generated Dish Descriptions
- Smart Menu Enhancement
- Faster Content Creation

---

# 🌟 Project Highlights

✅ Full Stack MERN Architecture

✅ JWT Authentication & Authorization

✅ RESTful API Development

✅ Stripe Payment Gateway Integration

✅ AI-powered Dish Description Generator 

✅ MongoDB Database Integration

✅ Secure Backend APIs

✅ API Testing 

✅ Responsive User Interface

✅ Production-inspired Food Ordering Workflow

---

# 🛠️ Tech Stack

### Frontend

- React.js
- HTML5
- CSS3
- JavaScript (ES6+)
- React Router DOM
- Axios

### Backend

- Node.js
- Express.js

### Database

- MongoDB
- Mongoose

### Authentication

- JWT Authentication
- bcrypt Password Hashing


### Version Control

- Git
- GitHub



# 🏗️ System Architecture

```
               React Frontend
                     │
                     │
              REST API Requests
                     │
          Express.js + Node.js
          │          │         │
          │          │         │
      MongoDB     Stripe     Grok AI
          │
     JWT Authentication
```

---

# 🔐 Authentication Flow

```
User Registration
        │
Password Hashing (bcrypt)
        │
Store User in MongoDB
        │
User Login
        │
JWT Token Generation
        │
Protected API Access
```

---

# 💳 Payment Workflow

```
Browse Menu
      │
Add Items to Cart
      │
Proceed to Checkout
      │
Stripe Payment Gateway
      │
Payment Verification
      │
Order Successfully Placed
      │
Track Order Status
```

---

# 🤖 Grok AI Workflow

```
Admin Creates Dish
        │
Send Prompt to Grok AI
        │
Generate Dish Description
        │
Save to MongoDB
        │
Display on Website
```

---

# 🌐 REST API Modules

### Authentication

- Register User
- Login User
- Get User Profile

### Restaurants

- Get Restaurants
- Add Restaurant
- Delete Restaurant

### Menu

- Get Menu
- Add Menu Item
- Delete Menu Item

### Cart

- Add to Cart
- Remove from Cart
- Update Quantity
- Get Cart

### Orders

- Place Order
- Get Orders
- Update Order Status

### Payments

- Create Stripe Checkout Session
- Verify Payment

---

# ⚙️ Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=4000

MONGO_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY

STRIPE_SECRET_KEY=YOUR_STRIPE_SECRET_KEY

GROK_API_KEY=YOUR_GROK_API_KEY
```

---

# 🚀 Installation & Setup

## Clone Repository

```bash
https://github.com/megharajmane07-mm/OrderIt_MERN-Project.git
```

## Navigate to Project

```bash
cd OrderIt_MERN_Project
```

## Install Client Dependencies

```bash
cd client
npm install
```

## Install Server Dependencies

```bash
cd ../server
npm install
```

## Start Backend

```bash
npm start
```

## Start Frontend

```bash
npm run dev
```

---

# 🎥 Live Demo

## 🍔 Part 1 – User Experience

### 🔗 Live Demo

https://www.linkedin.com/posts/megharajmane_mern-mongodb-expressjs-activity-7479532059225546752-vlRp

### Features Demonstrated

- User Registration
- Login Authentication
- Browse Restaurants
- Restaurant Menus
- Add to Cart
- Responsive User Interface

---

## 💳 Part 2 – Order & Stripe Payment

### 🔗 Live Demo

https://www.linkedin.com/posts/megharajmane_mern-mongodb-expressjs-activity-7480876626906640384-Xo8w

### Features Demonstrated

- Shopping Cart
- Stripe Payment Gateway
- Secure Checkout
- Order Placement
- Live Order Tracking

---

## 🤖 Part 3 – Admin Dashboard & AI

### 🔗 Live Demo

https://www.linkedin.com/posts/megharajmane_mern-mongodb-expressjs-ugcPost-7482005179660300288-UfxW/

### Features Demonstrated

- Admin Authentication
- Restaurant Management
- Menu Management
- Food Item Management
- AI Dish Description Generation using Grok AI

---

# 📚 Learning Outcomes

During this project, I gained hands-on experience in:

- Full Stack MERN Development
- React Component Architecture
- RESTful API Development
- MongoDB Database Design
- Authentication & Authorization
- Stripe Payment Integration
- AI API Integration (Grok AI)
- API Testing with Postman
- CRUD Operations
- Backend Security
- State Management
- Git & GitHub Workflow

---

# 🚀 Future Enhancements

- Google Authentication
- Email Verification
- OTP Login
- Wishlist
- Restaurant Ratings & Reviews
- Coupons & Offers
- Search & Filter
- Delivery Partner Module
- Push Notifications
- Admin Analytics Dashboard
- Docker Deployment
- CI/CD Pipeline
- Cloud Deployment

---

# 👨‍💻 Developer

## Megharaj Mane

🎓 **Bachelor of Engineering (B.E.) – Electronics & Telecommunication Engineering (ENTC)**

💻 **Aspiring Full Stack MERN Developer**

🚀 Passionate about building scalable web applications, backend systems, AI-powered solutions, and solving real-world problems through technology.

---

# 🤝 Connect With Me

### GitHub

https://github.com/megharajmane07-mm 

### LinkedIn

linkedin.com/in/megharajmane

---

# 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

## ⭐ If you found this project helpful, consider giving it a Star!

### Thank you for visiting my repository! ❤️

**Happy Coding 🚀**

</div>
