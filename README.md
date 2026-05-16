#  TaskNex

<div align="center">

### Smart Team Task Management Platform

TaskNex is a modern full-stack collaboration platform designed to help teams manage projects, organize workflows, track progress, and improve productivity through a clean Kanban-based task management system.

![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge\&logo=node.js)
![Express](https://img.shields.io/badge/Express.js-Framework-black?style=for-the-badge\&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge\&logo=mongodb)
![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-yellow?style=for-the-badge\&logo=javascript)
![JWT](https://img.shields.io/badge/JWT-Authentication-blue?style=for-the-badge)

</div>

---

#  Overview

TaskNex is a collaborative project and task management application built to simplify team workflow management. The platform allows organizations and teams to create projects, assign tasks, monitor progress, and manage team productivity efficiently.

The system provides:

* Secure authentication
* Role-based access control
* Project management
* Kanban-style task tracking
* Dashboard analytics
* Overdue task monitoring
* Team collaboration features

TaskNex is designed with scalability, clean architecture, and user experience in mind.

---

#  Key Features

##  Authentication & Security

* JWT-based secure authentication
* Password hashing using bcryptjs
* Protected API routes
* Secure session management

##  Role-Based Access Control

* ADMIN and MEMBER roles
* Permission-based project management
* Restricted task operations
* User-specific dashboard access

##  Project Management

* Create and manage projects
* Assign members to projects
* View complete project details
* Centralized workflow management

##  Task Management

* Create and assign tasks
* Set task deadlines
* Update task status dynamically
* Delete tasks (Admin only)
* Track task completion progress

##  Dashboard Analytics

* Total task statistics
* Pending task count
* In-progress tracking
* Completed task insights
* Overdue task detection

##  Kanban Workflow System

Tasks are organized into:

* 📝 TODO
* 🚧 IN_PROGRESS
* ✅ DONE

---

#  Tech Stack

| Category         | Technology                    |
| ---------------- | ----------------------------- |
| Frontend         | HTML, CSS, Vanilla JavaScript |
| Backend          | Node.js, Express.js           |
| Database         | MongoDB Atlas                 |
| Authentication   | JWT, bcryptjs                 |
| API Architecture | REST API                      |
| Deployment       | Railway                       |
| Version Control  | Git & GitHub                  |

---

#  System Architecture

```bash
Client (Frontend)
       ↓
Express REST API
       ↓
Authentication Middleware
       ↓
MongoDB Atlas Database
```

---

#  Project Structure

```bash
TaskNex/
│
├── public/
│   ├── index.html
│   ├── dashboard.html
│   ├── project.html
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       ├── auth.js
│       ├── dashboard.js
│       └── project.js
│
├── src/
│   ├── index.js
│   ├── db.js
│   │
│   ├── middleware/
│   │   └── auth.js
│   │
│   └── routes/
│       ├── auth.js
│       ├── projects.js
│       ├── tasks.js
│       ├── team.js
│       └── activity.js
│
├── seed.js
├── package.json
├── .env.example
└── README.md
```

---

#  Getting Started

Follow these steps to set up and run TaskNex locally.

## 1️. Clone the Repository

```bash
git clone https://github.com/your-username/tasknex.git

cd tasknex
```

---

## 2️. Install Dependencies

```bash
npm install
```

---

## 3️. Configure Environment Variables

Create a `.env` file in the root directory and add the following:

```env
MONGODB_URI=your_mongodb_connection_string
DB_NAME=tasknex
JWT_SECRET=your_secret_key
PORT=3000
```

---

## 4️. Run the Development Server

```bash
npm run dev
```

---

## 5️. Start the Production Server

```bash
npm start
```

---

#  Open in Browser

```bash
http://localhost:3000
```

---

#  Live Deployment

```bash
https://tasknexapp.up.railway.app/
```

---

#  Demo Credentials

## Admin Account

```txt
Email: admin@test.com
Password: admin123
```

## Member Account

```txt
Email: member@test.com
Password: member123
```

#  Role Permissions

| Action            | ADMIN | MEMBER |
| ----------------- | ----- | ------ |
| View Projects     | ✅     | ✅      |
| Create Projects   | ✅     | ❌      |
| Delete Projects   | ✅     | ❌      |
| Create Tasks      | ✅     | ✅      |
| Update Tasks      | ✅     | ✅      |
| Delete Tasks      | ✅     | ❌      |
| View Dashboard    | ✅     | ✅      |
| View Team Members | ✅     | ❌      |

---

#  Learning Outcomes

Through this project, I gained practical experience in:

* Full-stack web development
* REST API development
* Authentication & authorization
* Database design using MongoDB
* Role-based access control
* Deployment using Railway
* Backend architecture & middleware
* Team workflow system design

---

#  Future Enhancements

* Drag & Drop Kanban Board
* Real-Time Notifications
* Team Chat Integration
* File Attachments
* Dark Mode
* Activity Timeline
* Email Reminders
* WebSocket Integration
* Mobile Responsive Enhancements

---


# 📄 License

This project is developed for educational and learning purposes.


</div>
