🎓 College ERP – Frontend (Vite + React)

A modern, fast, and scalable College ERP Frontend built using Vite + React, featuring authentication, dashboards, modular pages, and API integration.
This project is structured to support real-world College/University management systems.

🚀 Features
🔐 Authentication

Login
Registration
Protected Routes
Token-based user sessions

*📊 Dashboard*
Student & Faculty profile display
Private API fetch example
Modular UI components

🏫 *ERP Modules (Extendable)*

Student Management
Faculty Management
Attendance System
Timetable
Exams & Results
Fee Management
Admin Controls

(Only core structure included — modules can be added as needed.)

*📦 Tech Stack*
Category	        Technology
Frontend Framework	React 18 + Vite
Routing	            React Router v6
API Calls	        Axios
Styling	            Custom CSS / Tailwind-ready
State	            React hooks (useState, useEffect)

**📁 Project Structure**

 College_ERP/
│  README.md
│  package.json
│  vite.config.js
│
└───src/
    │  App.jsx
    │  index.css
    │  main.jsx
    │
    ├── api/
    │    api.js
    │
    ├── pages/
    │    SignIn.jsx
    │    Register.jsx
    │    Dashboard.jsx
    │
    ├── components/
    │    Spinner.jsx


*🛠️ Installation & Setup*
1️⃣ Clone the repository
git clone https://github.com/yShukla00/College_ERP.git

cd College_ERP

2️⃣ Install dependencies
          npm install

3️⃣ Start the development server
          npm run dev


Your app runs on:

           👉 http://localhost:5173

🔌 API Configuration

You can set an API URL in .env:

           VITE_API_BASE=https://your-backend-url.com


Then your Axios instance uses:

import axios from "axios";

export default axios.create({
  baseURL: import.meta.env.VITE_API_BASE
});

🚀 Build for Production
npm run build


The output appears in the dist/ folder.

🤝 Contribution Guidelines

Fork repository

Create feature branch:

git checkout -b feature/new-feature


Commit changes

Push branch

Create a Pull Request

📄 License

This project is licensed under the MIT License, meaning you can use it freely for personal or commercial use.

❤️ Support the Project

If you like this project, give it a ⭐ on GitHub!
