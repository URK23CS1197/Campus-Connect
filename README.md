🏫 Campus-Connect

A modern full-stack web application designed to connect students, faculty, and campus resources in one unified digital platform. Campus-Connect provides announcements, events, profiles, and role-based access for a smarter campus experience.

📑 Table of Contents

    Overview

    Features

    Tech Stack

    Architecture

    Folder Structure

    Installation

    Backend Setup

    Frontend Setup

    Environment Variables

    API Summary

    Screenshots (Optional)

    Future Enhancements

    Contributing

    License

    Contact

🔍 Overview

Campus-Connect is built to serve as a digital hub for university life. It streamlines communication between students and faculty and improves access to campus information through announcements, event listings, user profiles, and role-based permissions.
The application follows a full MERN-style architecture with separate frontend and backend components for scalability and modularity.

✨ Features

    🔐 Secure Authentication (JWT-based login & registration)

    🎓 Role-Based Access Control (Student / Faculty / Admin)

    📢 Announcements Management (CRUD for authorized roles)

    📅 Events Management

    🧑‍🎓 User Profiles and search

    📡 RESTful API with clean endpoints
    
    🎨 Responsive and user-friendly UI

    ⚙️ Scalable architecture with decoupled frontend & backend

🛠 Tech Stack

    Frontend

        React

        React Router

        Axios

        CSS / Tailwind / Styled Components

    Backend

        Node.js

        Express.js

        MongoDB / Mongoose

        JWT Authentication

        bcrypt password hashing

    Developer Tools

        Nodemon

        ESLint + Prettier

        Git / GitHub

🏗 Architecture

    Frontend (React)
        ↓   REST API Calls
    Backend (Node + Express)
        ↓   CRUD operations
    MongoDB (Cloud / Local)


    Frontend handles UI, user interactions, routing

    Backend performs authentication, business logic, DB queries

    MongoDB stores all user, announcement, and event data

📁 Folder Structure

    Campus-Connect/
    │
    ├── frontend/
    │   ├── src/
    │   ├── public/
    │   └── package.json
    │
    ├── backend/
    │   ├── controllers/
    │   ├── models/
    │   ├── routes/
    │   ├── middleware/
    │   └── package.json
    │
    └── README.md

⚙️ Installation

    📌 Backend Setup
     cd backend
    npm install

Start the backend:

    npm start

🎨 Frontend Setup

    cd frontend
    npm install
    npm start

🔧 Environment Variables

    Create a .env file inside backend/:
    PORT=5000
    MONGO_URI=your_mongo_connection_url
    JWT_SECRET=your_secret_key
    (Optional) Inside frontend/:
    REACT_APP_API_URL=http://localhost:5000/api

📡 API Summary

    Authentication
        Method	Endpoint	Description
        POST	/api/auth/register	Register a user
        POST	/api/auth/login	Login and get JWT
        
    Announcements
        Method	Endpoint	Description
        GET	/api/announcements	Get all announcements
        POST	/api/announcements	Create announcement
        PUT	/api/announcements/:id	Update announcement
        DELETE	/api/announcements/:id	Delete announcement
    Users
        Method	Endpoint	Description
        GET	/api/users/me	Get logged-in user
        GET	/api/users	List all users
        
🖼 Screenshots
    



🚀 Future Enhancements

    📱 Mobile App Version (React Native)

    📬 Push Notifications

    💬 Real-time chat (Socket.io)

    🗂 Admin Dashboard

    🔔 Notification System

    🤝 Contributing

Fork the repository

    Create a new branch (feature/my-feature)

    Commit and push your changes

    Open a pull request

📜 License

    This project is licensed under the MIT License.

📬 Contact

    Developer: Niranson CDK
    GitHub: https://github.com/URK23CS1197
    Email: niransonk@gmail.com
