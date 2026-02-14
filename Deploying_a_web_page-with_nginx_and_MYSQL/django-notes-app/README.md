# 🚀 Production-Style Django Notes App Deployment using Docker, Nginx & MySQL

This project demonstrates how a real-world web application can be deployed using a multi-container architecture with Docker.  
It includes a Django web application served with Gunicorn, reverse-proxied by Nginx, and connected to a MySQL database.

The goal of this project is to practice **DevOps fundamentals**, containerization, and production-style deployment workflows.

---

## 🏗️ Architecture

Internet → Nginx (Reverse Proxy) → Django + Gunicorn → MySQL

---

## 🧰 Tech Stack

- Python (Django)
- Gunicorn (WSGI Server)
- Nginx (Reverse Proxy)
- MySQL 8.0
- Docker & Docker Compose
- Linux (Ubuntu)
- AWS EC2 (Cloud Deployment)

---

## ✨ Features

- Multi-container Docker architecture
- Reverse proxy configuration using Nginx
- Environment variables with `.env`
- Healthchecks for service readiness
- Persistent MySQL volume
- Service dependency management
- Production-style deployment structure

---

## 📂 Project Structure

Run Locally with Docker
1️⃣ Clone repository
git clone YOUR_REPO_URL
cd django-notes-app

2️⃣ Build & run containers
docker compose up --build

3️⃣ Open application
http://localhost
