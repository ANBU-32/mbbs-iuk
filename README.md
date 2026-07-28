# 🎓 MBBS Abroad Admission Portal

A modern, full-stack **MBBS Abroad Admission Portal** built with the **MERN Stack** that streamlines the complete student admission workflow. The platform enables students to apply for MBBS programs abroad while providing administrators with powerful tools to manage applications, student records, and admission processes efficiently.


## 📖 Overview

The MBBS Abroad Admission Portal is a comprehensive web application designed to digitize and simplify the overseas medical admission process. It provides a secure, scalable, and user-friendly environment for students, counselors, and administrators.

The application follows a modern client-server architecture using **React**, **Node.js**, **Express.js**, and **MongoDB**, with **JWT Authentication** ensuring secure access and role-based authorization.


# ✨ Features

### 👨‍🎓 Student Portal

* Student Registration & Login
* Secure JWT Authentication
* Apply for MBBS Abroad
* Complete Admission Workflow
* Upload Required Documents
* Application Status Tracking
* Profile Management
* Dashboard with Application Progress


### 👨‍💼 Admin Portal

* Admin Authentication
* Student Management
* Application Verification
* Approve / Reject Applications
* Manage Student Documents
* Dashboard Analytics
* Search & Filter Applications
* Update Admission Status


### 🔒 Security Features

* JWT Authentication
* Password Hashing
* Protected API Routes
* Role-Based Authorization
* Secure HTTP Requests
* Input Validation
* Error Handling Middleware


# 🏗️ Tech Stack

## Frontend

* React.js
* React Router DOM
* Axios
* Context API / Redux *(Optional)*
* CSS / Tailwind CSS / Bootstrap

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt.js

## Database

* MongoDB Atlas / Local MongoDB


# 📂 Project Structure

```text
mbbs-abroad-portal/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── services/
│   │   ├── context/
│   │   ├── routes/
│   │   ├── assets/
│   │   └── App.jsx
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── services/
│   ├── utils/
│   ├── uploads/
│   ├── app.js
│   └── server.js
│
├── .env
├── package.json
└── README.md

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/mbbs-abroad-portal.git
```

```bash
cd mbbs-abroad-portal
```

---

## Install Frontend

```bash
cd client
npm install
```

---

## Install Backend

```bash
cd ../server
npm install
```

---



# ▶️ Running the Project

## Backend

```bash
npm run dev
```

---

## Frontend

```bash
npm start
```

---

# 🔐 Authentication Flow

```text
User Login
      │
      ▼
Validate Credentials
      │
      ▼
Generate JWT Token
      │
      ▼
Store Token (HTTP-only Cookie or Local Storage)
      │
      ▼
Protected Routes
      │
      ▼
Authorized User Access
```

---

# 📊 Admission Workflow

```text
Student Registration
        │
        ▼
Login
        │
        ▼
Fill Admission Form
        │
        ▼
Upload Documents
        │
        ▼
Application Submission
        │
        ▼
Admin Review
        │
        ▼
Approve / Reject
        │
        ▼
Admission Status Updated
```

---

# 📦 REST API Modules

### Authentication

```http
POST   /api/auth/register
POST   /api/auth/login
GET    /api/auth/profile
```

### Students

```http
GET     /api/students
GET     /api/students/:id
POST    /api/students
PUT     /api/students/:id
DELETE  /api/students/:id
```

### Applications

```http
POST   /api/applications
GET    /api/applications
PUT    /api/applications/:id
DELETE /api/applications/:id
```

---

# 🛡️ Security Practices

* JWT-based Authentication
* Password Encryption using bcrypt
* Protected Routes
* Role-Based Authorization
* MongoDB Injection Protection
* Input Validation
* Centralized Error Handling
* Environment Variable Management

---

# 🚀 Future Enhancements

* Email Verification
* OTP Authentication
* PDF Admission Letter Generation
* Online Payment Gateway
* Real-Time Notifications
* AI-Based University Recommendations
* Chat Support
* Multi-Language Support
* Analytics Dashboard
* Document OCR Verification

---

# 📈 Performance Optimization

* Lazy Loading
* Code Splitting
* Optimized API Calls
* MongoDB Indexing
* Efficient State Management
* Response Compression
* Image Optimization

---

# 🧪 Testing

```bash
npm test
```

Recommended tools:

* Jest
* Supertest
* React Testing Library
* Postman

---

# 🤝 Contributing

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature/new-feature
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature/new-feature
```

5. Open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

**Your Name**

Full Stack MERN Developer

---

## ⭐ If you found this project useful, consider giving it a star on GitHub!
