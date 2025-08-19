# 🎨 Resource Management System – Frontend

## 📖 Overview
This is the **frontend** for the Resource Management System.  
It allows users to login, view resources, and admins to manage resources.

---

## ✨ Features
- 🔑 User Authentication (Login with JWT)  
- 👤 Role-based UI (Admin Dashboard, User Dashboard)  
- 📚 Resource Management (View, Add, Delete)  
- 🎨 Responsive UI with inline CSS  
- 🔗 API integration with backend  

---

## 🛠 Tech Stack
- **Frontend:** React (Vite)  
- **Routing:** React Router DOM  
- **State Management:** React Hooks + LocalStorage  
- **HTTP Client:** Axios  
- **Deployment:** Netlify / Vercel  

---

yaml

---

## ⚙️ Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/resource-management-frontend.git
   cd frontend
Install dependencies

bash
Copy code
npm install
Update API Base URL
Inside your Axios setup (or component where you call APIs):

js
Copy code
axios.defaults.baseURL = "https://your-backend.onrender.com/api";
Start the app

bash
Copy code
npm run dev
