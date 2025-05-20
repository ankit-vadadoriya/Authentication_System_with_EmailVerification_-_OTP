# 🔐 Authentication System with Email Verification & OTP (MERN Stack)

This is a full-stack authentication system built with React (Vite) on the frontend and Spring Boot on the backend. 
It features:
- User registration and login
- Email verification using OTP (One-Time Password)
- Forgot password functionality using OTP

## ✨ Features
✅ Register with username, email, and password

✅ Login securely with JWT (or session-based)

✅ Email verification via OTP

✅ "Verify Email" option visible until email is verified

✅ Password reset with email-based OTP

✅ Real-time feedback via toast notifications

## 🛠 Tech Stack
### Frontend (React + Vite)
- React.js
- Tailwind CSS
- Axios
- Toast notifications

### Backend (Java + Spring Boot)
- Core Java
- Spring Boot (REST APIs)
- Spring Security
- Java Mail Sender (for OTP emails)
- MySQL (database)
- Maven for dependency management

### 📬 Email & OTP
Email verification is triggered from the user's profile.

A 6-digit OTP is sent to the user's email.

The user enters the OTP to verify their email.

If successful, the "Verify Email" option is removed.

### 🔒 Forgot Password Flow
User clicks "Forgot Password"

Receives an OTP to their email

Enters the OTP and sets a new password
