# Photo Studio — Setup Guide

Welcome to the **Photo Studio Platform** setup guide. This system features a Next.js App Router frontend (with GSAP & Tailwind) and an Express.js + MongoDB backend.

- **GitHub Repository**: [https://github.com/JeevananthanV/photo-studio](https://github.com/JeevananthanV/photo-studio)
- **Author**: Jeevananthan V

---

## 📋 System Prerequisites

- **Node.js**: v18.0.0 or higher
- **npm**: v9.0.0 or higher
- **MongoDB**: Local MongoDB or MongoDB Atlas URI

---

## 📥 1. Clone the Repository

```bash
git clone https://github.com/JeevananthanV/photo-studio.git
cd photo-studio
```

---

## ⚙️ 2. Environment Variables Configuration

### Backend Environment (`backend/.env`)

```env
PORT=5000
NODE_ENV=development
MONGODB_URI=your_mongodb_connection_uri
JWT_SECRET=photo_studio_secret_jwt_2026
CLIENT_URL=http://localhost:3000
```

### Frontend Environment (`frontend/.env`)

```env
NEXT_PUBLIC_API_URL=http://localhost:5000
```

---

## 📦 3. Install Dependencies

```bash
# 1. Install Backend Dependencies
cd backend
npm install

# 2. Install Frontend Dependencies
cd ../frontend
npm install
cd ..
```

---

## 🚀 4. Running Locally

### Terminal 1: Backend Server (Port 5000)

```bash
cd backend
npm run dev
```

### Terminal 2: Frontend Client (Port 3000)

```bash
cd frontend
npm run dev
```
Open `http://localhost:3000` in your browser.

---

## 🏗️ 5. Production Build

```bash
cd frontend
npm run build
```

