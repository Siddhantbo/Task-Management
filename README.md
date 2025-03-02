# **Task Management Application**

This is a **Task Management Application** built with the **MERN stack**. The front end is developed using **React with Vite**, and the back end is built using **Express.js** with **MongoDB** as the database.

---

## 📜 Project Overview

A **task management app** that allows users to **organize personal and team-based tasks, track progress, and share task updates**. Users can create, assign, edit, and delete tasks while managing their workflow efficiently.

## **Features**

### **Core Functionalities**
- **User Authentication:**
  - Secure login and registration using JWT.
  - Password encryption with bcrypt.js.
- **Task Management:**
  - Create, update, and delete tasks with priority and due dates.
  - Organize tasks under Backlog, To-Do, In-Progress, and Done.
  - Overdue tasks highlighted in **red**, completed tasks in **green**.
- **User Management:**
  - Update profile details (name, email, password).
  - Security: Email/password changes require re-login.
- **Analytics & Filtering:**
  - View task analytics.
  - Filter tasks for **Today, This Week, or This Month**.
- **Collaboration:**
  - Add members to task boards and assign tasks.
- **User-Friendly Interface:**
  - Task tooltips for readability.
  - Notifications via toast messages.

## 🛠️ **Tech Stack**

### **Frontend**
- React (Vite) 
- Redux Toolkit (State Management)
- React Router DOM (Routing)
- React Toastify (Notifications)
- Tailwind CSS (Styling)

### **Backend**
- Express.js (Framework)
- MongoDB with Mongoose (Database)
- JWT (Authentication)
- Bcrypt.js (Password Encryption)
- Dotenv (Environment Variables)
- Cors (Cross-Origin Resource Sharing)

---

## **Setup Instructions**

### **Prerequisites**
- Install **Node.js (18.17.1)**
- Install **npm** or **yarn**
- Have a **MongoDB database** ready

### **Backend Setup**
```bash
cd backend
npm install
```
Create a `.env` file in the backend directory and add:
```env
MONGODB_URI=mongodb://127.0.0.1:27017/task_management
FRONTEND_URL=http://localhost:5173
PORT=9000
JWT_SECRET=your-secret-key
```
Start the server:
```bash
npm run dev
```

### **Frontend Setup**
```bash
cd frontend
npm install
```
Create a `.env` file in the frontend directory and add:
```env
VITE_BACKEND_URL=http://localhost:9000
VITE_FRONTEND_URL=http://localhost:5173
```
Start the frontend:
```bash
npm run dev
```
Open `http://localhost:5173` in your browser.

---

## **Scripts**

### **Frontend**
| Script | Description |
|--------|-------------|
| `npm run dev` | Start development server |
| `npm run build` | Build production version |
| `npm run preview` | Preview built application |

### **Backend**
| Script | Description |
|--------|-------------|
| `npm run dev` | Start backend in development mode |
| `npm run start` | Start backend in production mode |


## **Author**
Siddhant Borhade  
Email: siddhantborhade18.7@gmail.com.



---

🚀 **Feel free to contribute, report issues, or suggest improvements!** 😊
