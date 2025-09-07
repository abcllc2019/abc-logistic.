# ABC Logistic LLC Website

This is the official driver hiring portal for **ABC Logistic LLC**.

---

## 🚀 Features
- Public website for driver applications
- Online application form with document uploads
- Admin dashboard (secure login) to review applications
- Hiring details: pay, shifts, weekly pay, FAQ section

---

## 📂 Project Structure
- `frontend/index.html` → Public driver website
- `backend/server.js` → Node.js + Express backend
- `backend/public/admin.html` → Admin dashboard
- `backend/uploads/` → Uploaded driver documents
- `backend/.env` → Configuration (admin login, DB path)
- `backend/package.json` → Dependencies + start script
- `render.yaml` → Render deployment config

---

## 🔧 Setup Instructions (Local)

### 1. Install Requirements
- Install [Node.js](https://nodejs.org/) (v16+ recommended).

### 2. Run Backend
```bash
cd backend
npm install
npm start
```

The backend will start at: **http://localhost:4000**

### 3. Access Pages
- Public Website → [http://localhost:4000/](http://localhost:4000/)
- Admin Dashboard → [http://localhost:4000/admin.html](http://localhost:4000/admin.html)

---

## 🔑 Admin Login
- **Username:** JasmineFuqua73
- **Password:** Delivery123$

---

## 🌐 Deploy to Render (Free Hosting)

1. Push this project to **GitHub**:
```bash
git init
git add .
git commit -m "First commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/abc-logistic.git
git push -u origin main
```

2. Go to [Render.com](https://render.com) → **New Web Service**.  
3. Connect your GitHub repo.  
4. Render will auto-detect `render.yaml` and deploy.  
5. You’ll get a live domain like:  
   `https://abc-logistic.onrender.com`

---

## 📝 Notes
- All uploaded driver documents are stored in `/backend/uploads/`.
- Applications are stored in SQLite (`driver_apps.db`).
- Replace `backend/public/images/logo.jpg` with your own logo.
