# RepoSphere Backend ⚙️🚀  
A Node.js + Express backend powering **RepoSphere**, a GitHub-inspired mini Version Control System.  
This backend handles authentication, repository management, issues module, user profiles, and real-time socket updates.

---

## 🌐 Live Deployment Links

✅ **Backend API (Render):** https://vcs-backend-ynkn.onrender.com  
✅ **Frontend (AWS Amplify):** https://main.d1ca4l9j49evry.amplifyapp.com  

---

## 📌 Project Overview

RepoSphere backend is designed to support a lightweight version-control web platform where users can:

- Create an account and login securely  
- Create & manage repositories (public/private)  
- View repositories and repo details  
- Manage issues (create & list issues)  
- Fetch user profile details  
- Support real-time user room connection using Socket.IO  
- Perform CLI-based repo operations like init, add, commit, push, pull, revert (VCS features)

This backend also integrates MongoDB for database storage.

---

## 🛠️ Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB + Mongoose**
- **Socket.IO**
- **JWT Authentication**
- **Yargs CLI Commands**
- **CORS Enabled for Cross-Origin Requests**
- **Render Deployment**

---

## ✅ Features Implemented

### 🔑 Authentication
- Signup user
- Login user
- Token + userId stored and returned

### 📦 Repository System
- Create repository
- Fetch repositories (all + user-specific)
- Repo details via ID

### 🐞 Issues Module
- Create issue
- Fetch all issues

### 👤 User Profile
- Get user profile
- Update profile
- Delete profile
- Fetch all users

### ⚡ Real-Time
- Socket.IO room join support for per-user live updates

### 🖥️ CLI Based Mini Git Features
RepoSphere supports basic VCS operations via CLI:
- `init`
- `add`
- `commit`
- `push`
- `pull`
- `revert`

---

## 📁 Project Structure

```bash
backend/
│── config/                 # config files (if any)
│── controllers/            # controller logic (init/add/commit/push/pull/revert + user/repo/issue controllers)
│── middleware/             # middleware (auth etc.)
│── models/                 # MongoDB schemas
│── routes/                 # express routes (user/repo/issue/main)
│── .env                    # environment variables
│── index.js                # main server entry (yargs + express server)
│── package.json            # dependencies & scripts
│── README.md               # documentation

```

---

📌 Future Improvements

Add JWT protected routes properly

Add repo commits history UI

Add branching & PR support

Add issue assignment + comments

Add real-time repository updates

---

👤 Author

Rajmani
💻 Full Stack / Frontend Developer
🔗 GitHub: https://github.com/coder-rajmani

