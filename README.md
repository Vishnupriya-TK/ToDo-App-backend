
# 📝 ToDo List App

A **full-stack ToDo List web application** built using **HTML, CSS, JavaScript (Frontend)** and **Node.js, Express, MongoDB (Backend)**.
It provides **user authentication**, **theme switching**, and **comprehensive task management** with a clean, responsive UI.

---

## 🌐 Live Demo

🚀 **Frontend (Live App):** [https://todo-frontend-demo.vercel.app/](#)
🛠️ **Backend API (Render):** [https://todo-backend-api.onrender.com/](#)

---

## 🚀 Overview

The **ToDo List App** helps users manage daily tasks efficiently.
It includes secure user registration and login, dark/light theme toggle, and persistent data storage powered by MongoDB.

Users can **add, search, mark, delete, and view tasks** with real-time updates and smart alerts for each action.

---

## 🧩 Project Structure

```
Todo List/
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   └── style.css
│
└── backend/
    ├── server.js
    ├── package.json
    ├── models/
    │   ├── User.js
    │   └── Task.js
    └── .env
```

---

## ✨ Features

### 🔐 Authentication

* Register and login with username and password validation.
* Input fields clear automatically after success.
* Alert messages for success or error events.

### 🎨 Theme Toggle

* Switch between **dark** and **light** modes using the theme toggle button in the navbar.
* Selected theme persists via **localStorage**.

### ✅ Task Management

* **Add Tasks:**

  * Task title required (alert if empty).
  * Description and due date optional.
  * Inputs clear after adding a task.
  * Displays success alerts.

* **View Tasks:**

  * All tasks displayed in a table format.
  * Columns: checkbox, title, description, due date, delete button.
  * Due dates shown in ISO format (`2025-10-25T00:00:00.000Z`).

* **Toggle Completion:**

  * Checkbox to mark tasks as done/undone with alerts.

* **Delete Tasks:**

  * Delete individual tasks or clear all with a single alert.

* **Search:**

  * Filter tasks dynamically by title or description.

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript (Vanilla)

### Backend

* Node.js
* Express.js
* MongoDB with Mongoose

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Vishnupriya-TK/ToDo-App.git
cd ToDo-App
```

### 2. Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

Run the server:

```bash
node server.js
```

### 3. Frontend

Open `frontend/index.html` directly in your browser
or use **VS Code Live Server** to preview locally.

---

## 💡 Future Enhancements

* 🔒 JWT-based authentication
* 🗂️ Task prioritization (High/Medium/Low)
* 📅 Task sorting and filtering
* 📱 Fully responsive design
* 📧 Email verification

---

## 🧑‍💻 Author

**Vishnu Priya T K**
📍 [GitHub Profile](https://github.com/Vishnupriya-TK)


Would you like me to edit this README again **after you deploy your backend and frontend** (so I can fill in the correct live URLs for you automatically)?
