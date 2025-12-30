# 🔐 Google OAuth 2.0 Login – React + Node.js (SPA)

A complete, production-grade implementation of **Google OAuth 2.0 authentication** using:

- React (Single Page Application)
- Node.js + Express backend
- Passport Google OAuth 2.0 Strategy
- Secure cookie-based session handling

The project demonstrates **modern full-stack authentication architecture** used in real-world applications.

---

## 🚀 Demo Flow

1. User clicks **Sign in with Google**
2. User is redirected to **Google OAuth consent screen**
3. After successful login
   - backend verifies identity
   - secure session cookie created
4. User is redirected to **/profile**
5. Profile page displays:
   ✔ profile picture  
   ✔ name  
   ✔ email  
6. User can securely **Logout**

---

## ✨ Features

- ✅ Google OAuth 2.0 Login
- ✅ Node.js OAuth Proxy Backend
- ✅ Cookie-based authentication
- ✅ Authenticated profile page
- ✅ Secure logout flow
- ✅ Attractive glass-UI design
- ✅ React Router based SPA
- ✅ Error fallback (“Not Logged In”)
- ✅ Clean folder structure

---

## 🧩 Tech Stack

### Frontend
- React.js
- React Router DOM
- Fetch API
- Modern CSS UI

### Backend
- Node.js
- Express.js
- Passport.js
- passport-google-oauth20
- cookie-parser
- CORS
- JSON Web Token (JWT – optional future use)

---

## 📂 Project Structure

google-oauth-spa/
│
├── backend/ ← Node backend (OAuth & session)
│ └── server.js
│
├── frontend/ ← React Single Page Application
│ ├── src/
│ │ ├── App.js
│ │ ├── Profile.js
│ │ └── App.css
│
└── README.md ← You are reading this 🙂

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository

```bash
git clone <repo-url>
cd google-oauth-spa


2️⃣ Google Cloud Console configuration

Go to https://console.cloud.google.com

Create a project

Enable Google OAuth API

Configure OAuth consent screen

Create OAuth Client ID

Add:

Authorized JavaScript origin:
http://localhost:3000

Authorized redirect URI:
http://localhost:5000/auth/google/callback


Copy:

CLIENT_ID

CLIENT_SECRET

3️⃣ Backend Setup
cd backend
npm install


Add credentials in server.js or .env

GOOGLE_CLIENT_ID=xxxx
GOOGLE_CLIENT_SECRET=xxxx


Run backend

node server.js


Server runs on:

http://localhost:5000


4️⃣ Frontend Setup
cd frontend
npm install
npm start


App runs on:

http://localhost:3000


👤 Profile Page Preview

🖼 Profile picture

🧑‍💻 Full name

✉ Gmail email

🚪 Logout button


🔒 Security Practices Followed

✔ HTTP-only cookies
✔ OAuth 2.0 best practices
✔ No password stored
✔ Google verified identity
✔ CORS handled
✔ Token cleared on logout


🧭 Learning Outcomes

This project demonstrates:

understanding of OAuth 2.0

SPA authentication flow

session management

frontend-backend integration

secure logout implementation

working with Google Cloud Console

React Router based navigation

💼 Perfect for internships, resumes, viva & demo projects
