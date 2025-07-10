# 🎉Eventopia- Online Event Booking Platform — Containerization & Kubernetes Deployment

This project demonstrates a microservices-based **Online Event Booking Platform** containerized with Docker and deployed using Kubernetes. It showcases essential DevOps practices such as container orchestration, centralized configuration, ingress routing, and service scaling.

---

## 🧩 Microservices

| Service             | Tech Stack        | Database        |
|---------------------|-------------------|-----------------|
| 🧑‍💼 User Service     | FastAPI (Python)   | PostgreSQL      |
| 📅 Event Service     | Node.js (Express) | MongoDB         |
| 📝 Booking Service   | FastAPI (Python)   | PostgreSQL      |
| 🔔 Notification Service | Node.js (Express) | MongoDB         |
| 🌐 Frontend          | React.js          | —               |

Each service runs independently in its own container and communicates via internal networking.

---

## 🚀 Tech Stack

- **Frontend:** React.js  
- **Backend:** FastAPI & Node.js (Express)  
- **Databases:** PostgreSQL, MongoDB  
- **Containerization:** Docker, Docker Compose  
- **Orchestration:** Kubernetes (Minikube or Docker Desktop)  
- **Configs:** ConfigMaps, Secrets  

---
