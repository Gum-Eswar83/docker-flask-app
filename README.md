# 🚀 Dockerized Flask Application

## 📌 Project Overview

This project demonstrates how to containerize a simple Python Flask application using Docker.

The application runs inside a Docker container and is exposed to the local machine using port mapping.

---

## 🛠️ Technologies Used

- Python 3.9
- Flask
- Docker
- Git & GitHub

---

## 📂 Project Structure

```
docker-flask-app/
│
├── app.py
├── Dockerfile
├── requirements.txt
├── .gitignore
├── README.md
└── screenshots/
    └── output.png
```

---

## ⚙️ How To Run This Project

### 1️⃣ Clone the Repository

```
git clone https://github.com/Gum-Eswar83/docker-flask-app.git
cd docker-flask-app
```

---

### 2️⃣ Build Docker Image

```
docker build -t flask-docker-app .
```

This command:
- Reads the Dockerfile
- Installs dependencies
- Creates a Docker image

---

### 3️⃣ Run the Container

```
docker run -p 5000:5000 flask-docker-app
```

This command:
- Starts the container
- Maps container port 5000 to local port 5000

---

### 4️⃣ Open in Browser

Open your browser and visit:

```
http://localhost:5000
```

---

## ✅ Application Output

After running the container, the browser displays:

```
Hello Eswar! Docker is working
```

### 📷 Screenshot

![Application Output](screenshots/output.png)

---

## 🎯 Learning Outcomes

- Understanding Dockerfile creation
- Building Docker images
- Running containers
- Port mapping
- GitHub authentication using Personal Access Token
- End-to-end DevOps workflow

---

## 👨‍💻 Author

**Gumparlapati Eswar**

---

⭐ If you found this project helpful, share this repo and feel free to give it a star!