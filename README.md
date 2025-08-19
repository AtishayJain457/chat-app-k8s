# 💬 Chat App on Kubernetes

A full-stack **Chat Application** deployed using **Kubernetes (K8s)** on Minikube.  
This project demonstrates my ability to containerize applications, manage deployments, and orchestrate services using Kubernetes.

---

## 🚀 Tech Stack
- **Frontend:** React.js  
- **Backend:** Node.js (Express)  
- **Database:** MongoDB  
- **Containerization:** Docker  
- **Orchestration:** Kubernetes (Deployments, Services, PVC, Ingress/NodePort)  
- **CI/CD:** GitHub Actions  

---
```markdown
```
## ⚙️ How to Run Locally

### **1. Clone Repository**

git clone https://github.com/AtishayJain457/chat-app-k8s.git
cd chat-app-k8s

2. Start Minikube
minikube start

3. Apply Kubernetes Manifests
kubectl apply -f k8s/

4. Verify Deployments
kubectl get pods -n chat-app
kubectl get svc -n chat-app

6. Access Application
minikube service frontend -n chat-app




**✨ My Contributions

Created and configured Kubernetes manifests for frontend, backend, and MongoDB.

Integrated NodePort/Ingress for external access.

Set up Persistent Storage (PVC/PV) for MongoDB.

Implemented CI/CD workflow for deploying changes faster.

Customized README and documentation for professional project showcase.



🔮 Future Improvements

Implement WebSockets for real-time messaging.

Add Docker Compose for local non-K8s deployment.

CI/CD pipeline with Jenkins or GitHub Actions.

Add monitoring with Prometheus & Grafana.



📜 License

This project is for learning and demonstration purposes.
Feel free to fork and contribute! 🚀

**
