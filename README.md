# 🛡️ PaasOP - Password Manager

A simple and secure password manager built with **React (Vite)**, **Node.js**, **Express**, and **MongoDB**.

This app allows users to save, edit, view, and delete website login credentials. Designed for learning and local use.

---

## 🚀 Features

- 💾 Save passwords (site, username, password)
- 👁️ Toggle password visibility (eye/eyecross icons)
- 📋 Copy to clipboard
- ✏️ Edit and update passwords
- 🗑️ Confirm before delete
- 🔃 Synced with MongoDB
- ✅ Toast notifications for actions
- 🎯 Clean, responsive UI with Navbar & Footer

---

## 🛠️ Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Frontend   | React + Vite, Tailwind CSS, Toastify |
| Backend    | Node.js, Express    |
| Database   | MongoDB (local)     |

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Tarun-Gautam-915/PassOP-Mongo-Version.git
cd paasop-password-manager
```

### 2. Start the Backend

```bash
cd backend
npm install
node server.js
```

> Backend runs at: `http://localhost:3000`

Make sure MongoDB is running locally on `mongodb://localhost:27017`.

### 3. Start the Frontend

```bash
cd ..
npm install
npm run dev
```

> Vite will start your React app (usually on `http://localhost:5173`)

---

## 📁 Project Structure

```
PASSOP-MANAGER/
│
├── backend/
│   ├── server.js               # Express server
│   ├── .env                    # Environment variables
│   └── package.json            # Backend dependencies
│
├── public/
│   └── icons/                  # PNG icons used in the app
│       ├── eye.png
│       ├── eyecross.png
│       ├── github.png
│       ├── heart.png
│       └── favicon.png
│
├── src/
│   ├── assets/
│   │   └── react.svg
│   │
│   ├── components/
│   │   ├── Manager.jsx         # Main password manager UI
│   │   ├── Navbar.jsx          # Top navigation bar
│   │   └── Footer.jsx          # Bottom footer
│   │
│   ├── App.jsx                 # App layout and routing
│   ├── App.css
│   ├── index.css
│   └── main.jsx                # React entry point
│
├── index.html                  # Vite entry HTML
├── vite.config.js              # Vite config
├── package.json                # Frontend dependencies
└── README.md                   # You're here!
```

---

## 📷 Screenshots

### 🔐 Main Dashboard
<img width="1916" height="905" alt="image" src="https://github.com/user-attachments/assets/91413d4e-6a43-40cf-b656-bce20984b1b7" />


### 🔐 Mobile view
<img width="345" height="642" alt="image" src="https://github.com/user-attachments/assets/c3a9e8c7-f122-4eac-8607-548cc5ef040b" />


---

## 🧩 Recent Fixes

- ✅ Fixed new password overwrite issue by improving save logic
- ✅ Prevented toast from showing when delete was cancelled

---


## 👨‍💻 Author

Built by Tarun (https://github.com/Tarun-Gautam-915)  
Feel free to fork, contribute, or give a ⭐!

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
