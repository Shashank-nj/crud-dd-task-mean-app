# crud-dd-task-mean-app

A simple **CRUD MEAN application** (MongoDB, Express, Angular, Node.js) containerised with **Docker & Docker Compose**.  
It exposes a REST API in the backend and an Angular UI in the frontend to create, read, update and delete records.  
This project is part of an assignment to practice **Git, Docker, Docker Hub, and basic CI/CD on an Ubuntu VM**.

---

## 👤 Author

**Name:** Shashank NJ  
**GitHub:** [Shashank-nj](https://github.com/Shashank-nj)  
**Repository:** https://github.com/Shashank-nj/crud-dd-task-mean-app  

---

## 🧱 Tech Stack

- **Frontend:** Angular (Angular 15 CRUD app)
- **Backend:** Node.js + Express
- **Database:** MongoDB
- **Reverse Proxy:** Nginx
- **Containerisation:** Docker & Docker Compose
- **(Optional) CI/CD:** GitHub Actions → Ubuntu VM with Docker

---

## 🗂 Project Structure (high level)

```text
crud-dd-task-mean-app/
├─ backend/          # Express + Mongoose API
│  ├─ server.js
│  ├─ app/
│  │  ├─ models/    # Mongoose models
│  │  ├─ routes/    # Express routes
│  ├─ .env          # Backend environment variables (not committed)
│  └─ Dockerfile
├─ frontend/         # Angular application
│  ├─ src/
│  └─ Dockerfile
├─ nginx/
│  └─ conf.d/
│     └─ default.conf  # Nginx config (proxy to frontend/backend)
├─ docker-compose.yml
├─ README.md
└─ screenshots/      # (Optional) screenshots for assignment
