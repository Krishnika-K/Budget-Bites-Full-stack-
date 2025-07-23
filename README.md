# Budget-Bites-Full-stack-
# 🍽️ Budget Bites - Full Stack Food Ordering Web App

Budget Bites is a dynamic, full-stack food ordering platform that lets users browse a menu, place orders, and log in/sign up securely. Built using the MERN stack and deployed on **Vercel** (frontend) and **Railway** (backend).

---

## 🧩 Architecture Overview

[Frontend]
HTML + CSS + JS
|
▼ Fetch API
[Backend]
Node.js + Express
|
├── /api/menu → Retrieves menu items
├── /api/orders → Places/orders
└── /api/auth → Handles authentication
|
▼
[Database]
MongoDB (via Mongoose)

---

## 🚀 Live Links

- **Frontend (Vercel):** [🔗 Visit Budget Bites Frontend](https://budget-bites-full-stack.vercel.app/)
- **Backend (Railway):** [🔗 View API](https://budget-bites-backend-production.up.railway.app/)

---

## 🔧 Tech Stack

| Layer     | Technology                      |
|-----------|----------------------------------|
| Frontend  | HTML, CSS, JavaScript (Vanilla) |
| Backend   | Node.js, Express.js             |
| Database  | MongoDB Atlas                   |
| Auth      | JWT (JSON Web Token)            |
| Deployment| Railway (Backend), Vercel (Frontend) |

---

## 📂 Folder Structure

online-food/
├── client/ # Frontend HTML, CSS, JS
│ └── index.html
├── server/ # Backend logic
│ ├── models/ # Mongoose schemas
│ ├── routes/ # Express routes (menu, orders, auth)
│ ├── controllers/ # Logic for API endpoints
│ └── server.js # Entry point for backend
├── .env # Environment variables
└── README.md # Project documentation

---

🛠️ Features


View dynamic menu from backend

Place food orders

User login and signup with JWT authentication

MongoDB database integration

Fully deployed frontend and backend

---


🧪 How to Run Locally
  🖥️ Backend
        cd server
        npm install
        # create .env with:
        # MONGO_URI="mongodb+srv://krishnika:kkmckkmc@budget-bites-cluster.ivzf6jm.mongodb.net/budget-bites?retryWrites=true&w=majority"
        # JWT_SECRET="superSecureJwtSecret123!@#987"
        # PORT=5000
        node server.js
  🌐 Frontend
        cd client
        # Open index.html directly or use VS Code Live Server

---

🔧 Endpoints

| Route              | Method | Description              |
| ------------------ | ------ | ------------------------ |
| `/api/menu`        | GET    | Retrieve menu items      |
| `/api/auth/signup` | POST   | Register new user        |
| `/api/auth/login`  | POST   | Log in, receives JWT     |
| `/api/orders`      | POST   | Submit new order         |
| `/api/orders`      | GET    | (protected) Fetch orders |


---

📌 Future Enhancements

Add order history for users

Admin dashboard for restaurant

Add categories to menu

---

👨‍💻 Author
Krishnika K
GitHub: @Krishnika-K
