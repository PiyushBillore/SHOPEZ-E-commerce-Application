# SHOPEZ-E-commerce-Application

## ShopEZ – E-Commerce Platform (MERN Stack)

### 📌 Project Overview

**ShopEZ** is a full-stack e-commerce web application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.

The platform allows users to browse products, add items to their cart, and place orders, while administrators can manage products, categories, and orders.

This project demonstrates how a **modern e-commerce system can be built using full-stack JavaScript technologies**.

---

## 🎯 Objectives

* Build a complete **MERN stack e-commerce application**
* Provide users with a **smooth online shopping experience**
* Implement **backend APIs** for managing products, orders, and users
* Store and manage application data using **MongoDB**
* Develop an **interactive frontend using React.js**

---

## 🗂 Project Structure

```
ShopEZ
│
├── client
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   └── App.jsx
│   ├── index.html
│   └── package.json
│
├── backend
│   ├── config
│   │   └── db.js
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   ├── server.js
│   └── package.json
│
├── docs
├── README.md
└── user-flow
```

---

## 📊 Features

### User Features

* Browse product catalog
* View product details
* Add items to cart
* Place orders
* View order details

### Admin Features

* Manage products
* Manage categories
* View orders
* Manage inventory

---

## ⚙️ Technologies Used

### Frontend

* React.js
* HTML
* CSS
* JavaScript
* Vite

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose

### Tools

* Git
* GitHub
* MongoDB Atlas
* VS Code

---

## 🧠 Backend Architecture

The backend follows a **RESTful API architecture**.

```
Routes → Controllers → Models → Database
```

### Example API Flow

```
Client Request
      ↓
Express Route
      ↓
Controller Logic
      ↓
MongoDB Model
      ↓
Database Operation
      ↓
Response Sent to Client
```

---

## 🔄 Application Workflow

```
User visits website
      ↓
Browse products
      ↓
View product details
      ↓
Add item to cart
      ↓
Place order
      ↓
Order stored in MongoDB
      ↓
Admin manages orders/products
```

---

## 🚀 Running the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/PiyushBillore/SHOPEZ-E-commerce-Application.git
```

### 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

### 3️⃣ Configure Environment Variables

Create a **.env** file inside the backend folder.

```
MONGO_URI=your_mongodb_connection_string
PORT=5000
```

### 4️⃣ Run the Backend Server

```bash
node server.js
```

Server runs at:

```
http://localhost:5000
```

### 5️⃣ Run the Frontend

```bash
cd client
npm install
npm run dev
```

Frontend runs at:

```
http://localhost:5173
```

---

## 📈 Database

The project uses **MongoDB Atlas** as the cloud database.

Main collections:

* Users
* Products
* Orders
* Cart
* Admin

---

## 👨‍💻 Developer

**Piyush Billore**
Full Stack Developer (MERN Stack)

Responsibilities:

* Designed and developed the complete **ShopEZ platform**
* Built the **frontend using React.js**
* Developed **REST APIs using Node.js and Express.js**
* Integrated **MongoDB database using Mongoose**
* Implemented **product, cart, and order management system**

---

## 📌 Future Improvements

* Add **secure authentication using JWT**
* Integrate **online payment gateway**
* Implement **product reviews and ratings**
* Add **advanced search and filters**
* Deploy the application on **cloud platforms**

---

## 📜 License

This project is developed for **educational purposes** as part of the **SmartBridge SkillWallet program**.

---

## ⭐ Conclusion

ShopEZ demonstrates how a **complete MERN stack e-commerce platform** can be built using modern web technologies.

The system provides essential e-commerce features while showcasing key full-stack development concepts such as:

* API development
* Database integration
* Frontend-backend interaction
* RESTful architecture
