# 🚀 Full Stack Chat Application with Kubernetes Deployment

This repository contains my work on deploying a **Full Stack Chat Application** using **Docker and Kubernetes**.  
The application consists of a React frontend, Node.js/Express backend, and MongoDB database.  

I mainly focused on the **DevOps and deployment side** of this project.

---

## 🔹 My Contributions
- Containerized the application using **Docker**.
- Wrote **Kubernetes YAML manifests** for frontend, backend, and MongoDB.
- Configured **Persistent Volume & Persistent Volume Claim (PVC)** for MongoDB data.
- Exposed services using **NodePort** and tested with Minikube.
- Set up environment variables and `.env` files for secure configuration.
- Verified communication between pods using `kubectl logs` and `kubectl get svc`.

---

## 🔹 Tech Stack
- **Frontend:** React.js + TailwindCSS  
- **Backend:** Node.js + Express  
- **Database:** MongoDB  
- **Containerization:** Docker  
- **Orchestration:** Kubernetes (Minikube)  

---

## 🔹 Run Locally with Minikube

1. Start Minikube:
   ```bash
   minikube start
