# Advanced MERN To-Do Application — README.md

## 📌 Project Overview

This is a Full Stack MERN To-Do List Application developed using:

* Frontend: React.js
* Backend: Node.js with Express.js
* Database: MongoDB
* Authentication: JWT Authentication
* Architecture: MVC Pattern

The application allows users to manage tasks with complete CRUD operations, task status workflow, filtering, sorting, and secure authentication.

---

# 🚀 Features

✅ User Registration & Login
✅ JWT Authentication
✅ Complete CRUD Operations
✅ Task Status Workflow
✅ RESTful APIs
✅ Pagination Support
✅ Filtering & Sorting
✅ React Hooks & Reusable Components
✅ Server-side Validation
✅ Structured Error Handling
✅ MVC Architecture
✅ Responsive Design

---

# 🛠️ Technologies Used

## Frontend

* React.js
* Axios
* React Router DOM

## Backend

* Node.js
* Express.js

## Database

* MongoDB Atlas
* Mongoose ODM

## Authentication

* JWT (JSON Web Token)
* bcryptjs

## Other Packages

* dotenv
* cors
* nodemon

---

# 📂 Project Structure

```bash id="owiy20"
todo-app/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
│
└── README.md
```

---

# ⚙️ Installation Steps

# 1️⃣ Extract ZIP File

Extract the project folder.

---

# 2️⃣ Backend Setup

Open terminal inside:

```bash id="4xpczf"
todo-app/backend
```

---

# 3️⃣ Install Backend Dependencies

```bash id="ywmvtx"
npm install
```

OR manually install:

```bash id="v4j21n"
npm install express mongoose cors dotenv bcryptjs jsonwebtoken nodemon
```

---

# 🔐 Create Environment Variables

Create `.env` file inside backend folder.

Example:

```env id="b2d7nv"
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=mysecretkey
```

---

# 🌐 MongoDB Atlas Setup

## Step 1

Create MongoDB Atlas account.

## Step 2

Create cluster.

## Step 3

Click "Connect".

## Step 4

Copy MongoDB connection string.

Example:

```env id="98bafg"
mongodb+srv://username:password@cluster.mongodb.net/todoapp
```

Paste inside `.env`.

---

# ▶️ Start Backend Server

```bash id="xjlwmz"
npm run dev
```

OR

```bash id="9hzy5p"
node server.js
```

Expected Output:

```bash id="x1zogc"
Server running on port 5000
MongoDB Connected
```

---

# ⚛️ Frontend Setup

Open another terminal:

```bash id="om2xib"
cd frontend
```

---

# 📦 Install Frontend Dependencies

```bash id="krlt1u"
npm install
```

OR

```bash id="mmybjy"
npm install axios react-router-dom
```

---

# ▶️ Start React Application

```bash id="vjlwm4"
npm start
```

Application runs at:

```bash id="eckmso"
http://localhost:3000
```

---

# 🔑 Authentication APIs

## Register User

```http id="a9f96e"
POST /api/auth/register
```

### Request Body

```json id="47e94d"
{
  "name": "Hasini",
  "email": "hasini@gmail.com",
  "password": "123456"
}
```

---

## Login User

```http id="6pcq8v"
POST /api/auth/login
```

### Request Body

```json id="k8idib"
{
  "email": "hasini@gmail.com",
  "password": "123456"
}
```

---

# 📋 Task APIs

## Create Task

```http id="mnxwzv"
POST /api/tasks
```

---

## Get Tasks

```http id="pmfih2"
GET /api/tasks
```

---

## Update Task

```http id="vynyea"
PUT /api/tasks/:id
```

---

## Delete Task

```http id="x0rj44"
DELETE /api/tasks/:id
```

---

# 📊 Task Status Workflow

Available Task Status:

* Pending
* In-Progress
* Completed

---

# 🧩 Future Enhancements

* Drag & Drop Kanban Board
* Dark Mode
* Notifications
* Due Dates
* File Attachments
* Team Collaboration
* Role-based Access
* Redux Toolkit
* Search Functionality

---

# 🚀 Deployment

## Frontend

* Vercel
* Netlify

## Backend

* Render
* Railway

## Database

* MongoDB Atlas

---

# 🧪 Recommended Testing Tools

* Postman
* Thunder Client

---

# 👩‍💻 Author

Developed as an Advanced MERN Stack Internship Project.

---

# 📄 License

This project is for educational and internship purposes only.
