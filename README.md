# MERN Stack Application with Docker 🐳

This is a **MERN (MongoDB, Express.js, React.js, Node.js) application** that runs using **Docker and Docker Compose**. It includes:
- **Frontend** (React + Vite)
- **Backend** (Express.js + Node.js)
- **MongoDB** (Database)

## 📌 Prerequisites
Before running this project, make sure you have:
- **Docker** installed → [Download Docker](https://www.docker.com/get-started)
- **Git** installed → [Download Git](https://git-scm.com/downloads)

## 🚀 Installation and Setup

### 1️⃣ Clone the Repository
Open your terminal and run:
```sh
git clone https://github.com/your-username/your-repo.git
cd your-repo
```
### 2️⃣ Run the Application
Start all services (frontend, backend, and MongoDB) using:
```sh
docker-compose up --build
```
✅ **This will:**
- 🚀 Build the **frontend** and **backend**
- 🐳 Pull the latest **MongoDB** image
- ▶️ Start all services together

### 3️⃣ **Access the Application**
- 🌐 **Frontend:** [http://localhost:5173](http://localhost:5173)
- 📡 **Backend API:** [http://localhost:5050](http://localhost:5050)

### 🛑 **Stop the Application**
To stop the running containers, press **CTRL + C** or run:
```sh
docker-compose down
```

