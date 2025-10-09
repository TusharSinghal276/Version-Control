 🧭 Version Control System (VCS)

![React](https://img.shields.io/badge/Frontend-React.js-blue)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![Express.js](https://img.shields.io/badge/Framework-Express.js-lightgrey)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-brightgreen)

A **GitHub-style Version Control System** built using **React.js, Node.js, and Express.js**, allowing developers to perform core Git-like operations — such as `commit`, `add`, `push`, `pull`, and `revert` — through an interactive web interface.

## 🚀 Features

- 📁 **Repository Management:** Create and manage repositories directly in the browser  
- 💾 **Commit System:** Track file changes with commit messages and timestamps  
- 🔄 **Push & Pull Operations:** Simulate remote synchronization between local and server branches  
- 🌿 **Branching & Merging:** Manage multiple branches with conflict handling  
- 🕒 **Commit History:** Visual timeline of changes for each repository  
- 💬 **User Interface:** Responsive React.js dashboard for all operations  
- ⚙️ **API Integration:** RESTful backend built with Node.js & Express.js  

---

## 🧑‍💻 Tech Stack

| Category | Technologies |
|-----------|---------------|
| **Frontend** | React.js, HTML, CSS, JavaScript |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB |
| **Version Control** | Git, GitHub |
| **Core Concepts** | REST APIs, Branching, Versioning, MVC Architecture |

---

## 📂 Project Structure

```

VersionControlSystem/
│
├── /client (React Frontend)
│   ├── /src
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── services/
│   └── package.json
│
├── /server (Node Backend)
│   ├── app.js
│   ├── /routes
│   ├── /controllers
│   ├── /models
│   ├── package.json
│   └── .env
│
└── README.md

````

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/Version-Control-System.git
cd Version-Control-System
````

### 2️⃣ Setup the Backend

```bash
cd server
npm install
```

Create a `.env` file inside `/server`:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Run the backend:

```bash
npm start
```

### 3️⃣ Setup the Frontend

Open a new terminal:

```bash
cd client
npm install
npm start
```

### 4️⃣ Access the App

```
http://localhost:3000
```

## 🧠 Key Learning Outcomes

* Learned **versioning concepts** and simulated them in full-stack architecture
* Implemented **branch management** and **commit tracking** using REST APIs
* Strengthened **React–Express integration** for real-time data updates
* Practiced modular coding and **MVC design pattern**
* Enhanced skills in **API communication** and **state management**

---

## 🧩 Future Enhancements

* 🧮 Real Git command integration (for educational demo)
* 🔐 User authentication & role-based access
* 🧰 File diff visualization (using code comparison libraries)
* ☁️ Cloud deployment on Render / Vercel / AWS

---

## 🧑‍🎓 Author

**Tushar Singhal**
📧 [singhaltushar@gmail.com](mailto:singhaltushar@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/tushar-singhal-1b3987295/) | [GitHub](https://github.com/TusharSinghal276)

⭐ **If you find this project useful, please give it a star on GitHub!**

