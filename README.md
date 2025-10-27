# 🧩 MeowCollab – Real-Time Collaborative Code Editor

## 🚀 Overview

**MeowCollab** is a full-stack web platform that enables developers, students, and teams to **write, run, and collaborate on code in real time** — directly from their browsers.  

It combines a powerful live code editor, secure backend execution, and instant synchronization, making it perfect for **pair programming, coding interviews, hackathons, and online classrooms**.

---

## ⚙️ Core Features

### 🧠 1. Real-Time Collaborative Editor
- Multiple users can edit the same file simultaneously  
- Live cursor tracking and syntax highlighting  
- Built using **Socket.IO** for smooth, low-latency updates  
- Instant synchronization across all connected users  

### 💻 2. Code Execution (Multi-Language Support)
- Supports **JavaScript, Python, C, C++, and Java**  
- Executes code securely in **Docker containers**  
- Real-time output and error logs in the console  

### 👥 3. User Authentication & Rooms
- Secure **sign-up / login** using email and password  
- Create or join collaborative rooms via unique shareable links  
- Sessions managed with **JWT (JSON Web Token)** authentication  

### 💾 4. Project & File Management
- Create and organize files/folders inside projects  
- Autosave progress to the database using **Prisma ORM**  
- Share project URLs with collaborators  

### 💬 5. Built-in Chat & Presence
- Real-time chat panel within each workspace  
- See who’s currently online and editing  

### 🎨 6. Modern Developer Interface
- Clean, responsive UI with a **blue-accented dark theme**  
- Built using **React + Vite + Tailwind CSS**  
- Editor powered by **Monaco Editor** (used in VS Code)  

---

## 🧱 Tech Stack

| Layer | Technology |
|:------|:------------|
| **Frontend** | React (Vite), Tailwind CSS, Monaco Editor |
| **Backend** | Node.js (Express), Prisma ORM |
| **Database** | MySQL / PostgreSQL |
| **Realtime Collaboration** | Socket.IO |
| **Code Execution** | Docker Sandbox |
| **Authentication** | JWT (JSON Web Token) |
| **Deployment** | Vercel (Frontend) + Railway / Render (Backend) |

---

## 🧩 Project Architecture
frontend/
├─ src/
│ ├─ components/
│ ├─ pages/
│ ├─ context/
│ └─ utils/
├─ package.json
└─ vite.config.js

backend/
├─ src/
│ ├─ routes/
│ ├─ controllers/
│ ├─ services/
│ ├─ prisma/
│ └─ utils/
├─ Dockerfile
├─ package.json
└─ server.js

