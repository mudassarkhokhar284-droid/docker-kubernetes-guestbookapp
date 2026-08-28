# 🐳 Kubernetes & Docker Guestbook Application

A cloud-native multi-tier Guestbook application deployed and managed using Docker containers and Kubernetes orchestration. This project demonstrates foundational DevOps workflows, including containerization, deployment configurations, and service scaling in a cloud environment.

---

## 🚀 Project Overview
The Guestbook application allows users to submit and view messages stored via a backend infrastructure. The architecture utilizes containerized frontend components managed dynamically through Kubernetes manifests, ensuring high availability, load balancing, and resource management.

---

## 🛠️ Tech Stack & Tools
* **Containerization:** Docker
* **Orchestration:** Kubernetes (Deployments, Services, HPA)
* **Languages & Frameworks:** Go, Node.js, jQuery, HTML/CSS
* **Version Control:** Git & GitHub

---

## 📁 Project Architecture & Structure
* `Dockerfile` - Instructions for containerizing the application components.
* `deployment.yml` - Kubernetes configuration for pod deployment, replica management, and container specifications.
* `app/` & `main.go` - Application source code and backend logic.
* `public/` - Frontend assets (HTML, JavaScript, CSS).
* `hpa` / `hpa2` - Horizontal Pod Autoscaler configurations for dynamic scaling.

---

## ⚙️ Key DevOps & Orchestration Concepts Implemented
1. **Container Packaging:** Built and managed lightweight application images using Docker.
2. **Kubernetes Deployment:** Configured declarative deployment YAML files to manage pod life cycles and ensure zero-downtime rolling updates.
3. **Service Exposure:** Set up networking components to route internal and external traffic reliably.
4. **Autoscaling:** Implemented Horizontal Pod Autoscaling (HPA) to scale application replicas based on CPU utilization and traffic load.

---

## 💡 Author
**Mudassar Ahmed**  
*Undergraduate Computer Science Student | DevOps & Cloud *
