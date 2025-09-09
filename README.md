# 🚀 Digital Agency Website (Full Stack)

A full-stack **digital agency website** built with:

- **Frontend:** HTML, TailwindCSS, JavaScript  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  

Includes a dynamic **consultation form** with an **admin dashboard** (view, delete, export to CSV) and **secure login**.

## ⚡ Features

✅ Consultation form with validation  
✅ Stores submissions in MongoDB  
✅ Admin login (session-based authentication)  
✅ Admin dashboard (view, delete, export submissions)  
✅ Export data to CSV for reporting  
✅ Clean Tailwind-based UI  

---

## 🔧 Installation & Setup

### 1. Clone project
```bash
git clone <your-repo-url>
cd agency-fixed
```

### 2. Install backend dependencies
```bash
cd Backend
npm install
```

### 3. Start MongoDB
Make sure MongoDB is installed and running:
```bash
mongod
```

### 4. Start backend server
```bash
node server.js
```

✅ You should see:
```
🚀 Server running on http://localhost:5000
✅ MongoDB connected
```

---

## 🎨 Frontend Usage

- Open `Frontend/index.html` in your browser.  
- Fill out the consultation form.  
- Submissions will be stored in MongoDB.  

---

## 🔑 Admin Panel

- Open: [http://localhost:5000/admin/login](http://localhost:5000/admin/login)  
- Default credentials:  
  - **Username:** `admin`  
  - **Password:** `12345`  

⚠️ Change these in `server.js` for production use.

---

## 📊 Admin Features

- View all consultation submissions  
- Delete submissions  
- Export submissions as **CSV**  
- Logout functionality  

---

## 🚀 Workflow Summary

1. Start **MongoDB** → `mongod`  
2. Start **Backend** → `node server.js`  
3. Open **Frontend** → `Frontend/index.html`  
4. Access **Admin** → [http://localhost:5000/admin/login](http://localhost:5000/admin/login)  
## 📄 License

MIT License – free to use and modify.
