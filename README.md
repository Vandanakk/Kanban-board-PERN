# Kanban Board — Full Stack Task Manager

A full-stack Kanban-style task management web application built with the PERN stack. Supports drag-and-drop task tracking, user authentication, and persistent storage.

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React, CSS |
| Backend | Node.js, Express.js |
| Database | PostgreSQL |
| Auth | JWT (JSON Web Tokens) |
| Deployment | Render |

## ✨ Features

- Drag-and-drop task management across columns (To Do, In Progress, Done)
- User registration and login with JWT authentication
- Persistent task storage with PostgreSQL
- REST API with full CRUD operations
- Protected routes — each user sees only their own tasks

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/kanban-board-pern.git
cd kanban-board-pern

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install

# Set up environment variables
# Create a .env file in /server with:
# DATABASE_URL=your_postgresql_connection_string
# JWT_SECRET=your_secret_key

# Run backend (from /server)
npm start

# Run frontend (from /client)
npm start
```

## 📁 Project Structure

```
kanban-board-pern/
├── client/          # React frontend
│   ├── src/
│   │   ├── components/
│   │   └── App.jsx
├── server/          # Express backend
│   ├── routes/
│   ├── middleware/
│   └── index.js
└── README.md
```

## 📌 What I Learned

- How data flows between a React frontend and an Express backend
- Implementing JWT authentication — token creation, storage, and verification
- Designing a relational PostgreSQL schema with foreign key constraints
- Deploying a full-stack Node.js app on Render

## 🔗 Live Demo

[View deployed app](https://your-render-link.onrender.com) *(link will be added after deployment)*
Copy
