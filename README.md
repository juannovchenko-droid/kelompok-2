# kelompok-2
PROJECT UI/UX KELOMPOK 2

Nama repo: math1-fullstack
Deskripsi: 🌟 Website Matematika 1 Lengkap (Backend + Frontend)

math1-fullstack/
├── 📁 backend/           ← Backend Node.js
│   ├── 📄 server.js
│   ├── 📄 package.json
│   ├── 📄 .env.example
│   └── 📄 isi-data.js
├── 📁 frontend/          ← Frontend HTML/CSS/JS
│   ├── 📄 index.html
│   ├── 📄 kategori.html
│   ├── 📄 materi.html
│   ├── 📁 css/
│   │   └── 📄 style.css
│   └── 📁 js/
│       └── 📄 main.js
├── 📄 README.md          ← Dokumentasi
├── 📄 .gitignore
└── 📄 deploy.sh          ← Auto deploy

{
  "name": "math1-backend",
  "version": "1.0.0",
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  },
  "dependencies": {
    "express": "^4.18.2",
    "mongoose": "^7.5.0",
    "dotenv": "^16.3.1",
    "cors": "^2.8.5"
  },
  "devDependencies": {
    "nodemon": "^3.0.1"
  }
}

MONGODB_URI=mongodb://localhost:27017/math1
PORT=5000

MONGODB_URI=mongodb://localhost:27017/math1
PORT=5000

# 🧮 **Math1 - Website Matematika 1 FULLSTACK** 🌟

Website belajar **Matematika 1** lengkap dengan **Backend + Frontend**!

## ✨ **FITUR**
- ✅ **5 Kategori**: Sistem Bilangan Real, Fungsi, Limit, Turunan, Integral
- ✅ **Rumus + Contoh + Latihan Soal**
- ✅ **Search materi**
- ✅ **Responsive Mobile**
- ✅ **Modern Design**

## 🚀 **Cara Jalanin Lokal**

### **1. Backend**
```bash
cd backend
npm install
cp .env.example .env
node isi-data.js  # Masukin data contoh
npm run dev

cd frontend
# Buka index.html di browser
# ATAU: npx live-server

Backend: http://localhost:5000/api/kategori
Frontend: http://localhost:8080 (live-server)

Frontend: HTML5 + CSS3 + Vanilla JS
Backend: Node.js + Express + MongoDB
Deploy: Render + Netlify (GRATIS)

GET /api/kategori     → List kategori
GET /api/materi/:kategori → Materi per kategori
GET /api/cari?q=...   → Search
GET /api/materi/:id   → Detail materi


---

## 🗑️ **6. .gitignore**


---

## 🎯 **7. COMMANDS GIT (COPY PASTE)**
```bash
# 1. Buat folder + clone
mkdir math1-fullstack
cd math1-fullstack
git init
git add .

# 2. Commit
git commit -m "🚀 Math1 Fullstack v1.0 - Backend + Frontend siap!"

# 3. Push ke GitHub
git remote add origin https://github.com/username/math1-fullstack.git
git branch -M main
git push -u origin main


---

## 🎯 **7. COMMANDS GIT (COPY PASTE)**
```bash
# 1. Buat folder + clone
mkdir math1-fullstack
cd math1-fullstack
git init
git add .

# 2. Commit
git commit -m "🚀 Math1 Fullstack v1.0 - Backend + Frontend siap!"

# 3. Push ke GitHub
git remote add origin https://github.com/username/math1-fullstack.git
git branch -M main
git push -u origin main

[build]
  publish = "frontend"
  command = "echo 'Frontend static only!'"

✅ Repo: math1-fullstack
✅ Backend: Node.js + MongoDB
✅ Frontend: HTML/CSS/JS cantik
✅ README lengkap
✅ Deploy instructions
✅ .gitignore
✅ Data contoh

Backend: https://math1-backend.onrender.com
Frontend: https://math1.netlify.app

5 menit → Copy files
2 menit → npm install + isi-data.js
1 menit → git push
0 menit → Buka index.html

 math1-fullstack/
   backend/      5 files
   frontend/     6 files  
   README.md     ⭐⭐⭐⭐⭐





