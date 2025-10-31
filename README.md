# 🌀 Parlen3D  
**Simplicity-first 3D modeling for everyone.**

Parlen3D is a new approach to 3D creation — designed to make modeling intuitive and accessible without sacrificing power.  
It’s built for creators who want to focus on ideas, not interfaces.

---

## 🌍 Vision
Parlen3D bridges the gap between ease of use and professional capability.  
Users can model, customize, and share 3D designs effortlessly through **templates** and **creator-defined UIs** — no steep learning curve, no cluttered menus.

---

## ✨ Key Features
- **Simplicity-first interface** – modeling through guided controls and templates.  
- **Template system** – creators define how others interact with 3D assets.  
- **Community Hub** – share, remix, and collaborate on models and scripts.  
- **API-first backend** – Laravel + MySQL for scalable data management.  
- **Modern frontend** – React + Three.js for real-time visualization.  
- **Collaboration** – powered by Yjs for real-time editing and shared sessions.  

---

## 🧩 Tech Stack
| Layer | Technology |
|-------|-------------|
| **Frontend** | React, Next.js, react-three-fiber |
| **Backend** | Laravel (API-first) |
| **Database** | MySQL |
| **Storage** | AWS S3 (or compatible) |
| **Realtime** | Yjs, WebSockets |
| **Auth** | Laravel Sanctum / JWT |

---

## 🛠️ Setup (Development)
```bash
# Clone the repository
git clone https://github.com/SoftCircuitFm/parlen3d.git
cd parlen3d

# Install backend
cd backend
composer install
cp .env.example .env
php artisan key:generate

# Install frontend
cd ../frontend
npm install
npm run dev
