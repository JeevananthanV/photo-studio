# 📸 Photo Studio — Premium Photography Platform

[![Repository](https://img.shields.io/badge/GitHub-JeevananthanV%2Fphoto--studio-blue?logo=github)](https://github.com/JeevananthanV/photo-studio)
[![Next.js](https://img.shields.io/badge/Next.js-App%20Router-black?logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Express](https://img.shields.io/badge/Backend-Express.js-339933?logo=express&logoColor=white)](https://expressjs.com)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB%20%2B%20Mongoose-47A248?logo=mongodb&logoColor=white)](https://www.mongodb.com)
[![TailwindCSS](https://img.shields.io/badge/UI-Tailwind%20%2B%20shadcn-38B2AC?logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

A highly visual, modern, and premium photography studio website engineered with Next.js, GSAP animations, Framer Motion, and a Node.js + MongoDB backend.

---

## 🔗 Repository Links

| Detail | Link |
|---|---|
| **GitHub Repository** | [https://github.com/JeevananthanV/photo-studio](https://github.com/JeevananthanV/photo-studio) |
| **Author** | [Jeevananthan V](https://github.com/JeevananthanV) |
| **Frontend Portal** | `http://localhost:3000` |
| **Backend API** | `http://localhost:5000` |

---

## 🏗️ Architecture Overview

- **Frontend**: Next.js App Router, Tailwind CSS, shadcn/ui primitives, GSAP cinematic scroll triggers, and Framer Motion transitions.
- **Backend**: Express.js REST API, Mongoose ORM, structured controllers, booking inquiry management, and portfolio gallery endpoints.
- **Deployment**: Ready for Vercel (frontend) and Render / VPS (backend).

---

## 📁 Project Structure

```
photo-studio/
├── frontend/             # Next.js App Router (JS, Tailwind, shadcn/ui)
│   ├── app/              # Main App routing and entry points
│   ├── components/       # Custom components & gallery views
│   ├── components/ui/    # shadcn/ui base elements
│   ├── lib/              # Frontend utilities and configs
│   ├── public/           # High-resolution assets
│   └── .env.example      # Frontend environment template
│
├── backend/              # Node + Express API
│   ├── src/
│   │   ├── config/       # MongoDB connection & config
│   │   ├── controllers/  # API controllers
│   │   ├── models/       # Mongoose models (Inquiry, Gallery, Review)
│   │   ├── routes/       # Express routes
│   │   ├── middleware/   # Request validation & error handling
│   │   └── server.js     # Server entry point
│   ├── .env.example      # Backend environment template
│   └── package.json      # Dependencies and scripts
│
├── .gitignore            # Shared Git ignore configurations
├── render.yaml           # Render deployment blueprint
└── vercel.json           # Vercel deployment configuration
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v18.x or higher)
- npm (v9.x or higher)
- MongoDB instance (Atlas or local)

### Clone

```bash
git clone https://github.com/JeevananthanV/photo-studio.git
cd photo-studio
```

### Installation

```bash
# Frontend dependencies
cd frontend
npm install

# Backend dependencies
cd ../backend
npm install
```

### Running Locally

#### Running Frontend (Next.js)
```bash
cd frontend
npm run dev
```
Available at `http://localhost:3000`.

#### Running Backend (Express)
```bash
cd backend
npm run dev
```
Available at `http://localhost:5000`.

---

## 👨‍💻 Author

**Jeevananthan V** — [@JeevananthanV](https://github.com/JeevananthanV)

## License

MIT
