# 🔐 IPT 2026 – Full-Stack Authentication App

**A full-stack user authentication and account management system with an Angular frontend and a Node.js + TypeScript backend.**

Built for our Integrative Programming and Technologies (IPT) course.

## ✨ Features

- Sign up with **email verification**
- Log in with **JWT** + **refresh tokens** (auto-refresh in the frontend)
- Forgot / reset password
- View and update your profile
- **Admin area** to list, add, edit and delete accounts
- **Role-based** route guards (Admin / User)
- Swagger API documentation

## 🛠️ Tech Stack

| Part | Technology |
|---|---|
| Frontend | Angular, TypeScript |
| Backend | Node.js, Express, TypeScript |
| Database | MySQL (Sequelize) |
| Auth | JWT, refresh tokens, bcrypt |
| Docs | Swagger |

## 📁 Project Structure

```
backend/    Express + TypeScript API (accounts, auth, email, swagger)
frontend/   Angular app (account, admin, profile, home)
```

## 🚀 Getting Started

**Requirements:** Node.js 18+, MySQL, Angular CLI

**Backend**
```bash
cd backend
npm install
npm run start:dev      # runs on http://localhost:4000
```
Set your database and JWT settings with environment variables (`DB_HOST`, `DB_USER`, `DB_PASSWORD`, `DB_NAME`, `JWT_SECRET`).

**Frontend**
```bash
cd frontend
npm install
ng serve               # opens on http://localhost:4200
```
