  # 📚 Library Management System (MERN Stack)

A web-based library management system designed to manage books, users, and daily library operations efficiently. [cite_start]This system helps librarians organize book records, issue and return books, and generate useful reports[cite: 4, 5].                                                         
                                                                                                            
## 🚀 Project Overview                                                                                                                                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                                                     
This project is a Single Page Application (SPA) built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). [cite_start]It replaces manual library methods with a centralized digital database to track inventory and loans[cite: 30].
                                                                                                            
### Key Features (Modules)                                                                                                                 
The system is divided into 5 distinct modules, each with full **CRUD** (Create, Read, Update, Delete) capabilities:

1.  **👥 Member / Student Management:** Register, view, update, and deactivate student profiles.                                 
2.  **📦 Supplier & Donation Management:** Manage book suppliers and donation records.
3.  **📚 Book Inventory Management:** Cataloging system to add, search, and manage book stock.                                        
4.  **🔄 Circulation Management:** Handle book issuing (loans) and returns (transactions).
5.  **📢 Announcement Management:** Post and manage library news and notices on the dashboard.

---

## 🛠️ Tech Stack

* **Frontend:** React.js, React Router, Axios, CSS/Bootstrap/Tailwind
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Atlas or Local)
* **Tools:** Postman (API Testing), GitHub (Version Control)

---

## 📂 Project Structure

```bash
/Library-Management-System
│
├── /FRONTEND                 # Frontend (React Application)
│   ├── /src
│   │   ├── /components     # Reusable UI components
│   │   ├── /pages          # Main pages (Dashboard, AddBook, etc.)
│   │   └── App.js
│   └── package.json
│
├── /BACKEND                 # Backend (Node.js & Express)
│   ├── /models             # Mongoose Schemas (Book.js, Student.js, etc.)
│   ├── /routes             # API Endpoints
│   ├── /controllers        # Logic for CRUD operations
│   ├── server.js           # Server entry point
│   └── .env                # Environment variables
│
└── README.md
