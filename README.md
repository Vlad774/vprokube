# 🚀 App Kubernetes Deployment on AWS
Automated, Scalable, and Secure Web Application Deployment

##  📌 Description
This project automates the deployment of the web application on a Kubernetes cluster using KOps, AWS,
and containerized services. It ensures scalability, high availability, and resilience with
minimal manual intervention.

## 🛠Technologies
- Kubernetes + KOps → Cluster orchestration & automation on AWS.
- Docker → Containerized services (Tomcat, MySQL, RabbitMQ, Memcached).
- AWS (EBS, ALB, Route 53) → Storage, load balancing & DNS.
- NGINX Ingress Controller → Manages external traffic via ALB.
- Kubernetes Secrets & PVCs → Secure credentials & persistent storage.
  
## 🔄 Deployment Workflow
- 1️⃣ Cluster Setup → KOps provisions a Kubernetes cluster on AWS.
- 2️⃣ Service Deployment → Tomcat, MySQL, RabbitMQ, and Memcached run as Deployments.
- 3️⃣ Networking & Scaling → ClusterIP for internal services, Ingress + ALB for public access.
- 4️⃣ Persistence & Security → EBS volumes for MySQL, Secrets for credentials.
- 5️⃣ Auto-healing & Scaling → Kubernetes ensures resilience and performance.
     
## ✨ Key Features
- ✔ Fully automated Kubernetes deployment
- ✔ Self-healing & auto-scaling for high availability
- ✔ Persistent storage with AWS EBS
- ✔ Ingress with ALB & Route 53 for external access
- ✔ Infrastructure as Code (IaC) with KOps
 
## Walk-through:

 ![First try](https://github.com/Vlad774/vprokube/blob/main/diagramm.png) 
 ![First try](https://github.com/Vlad774/vprokube/blob/main/kubedefs.png) 
 ![First try](https://github.com/Vlad774/vprokube/blob/main/pods_running.png)
 ![First try](https://github.com/Vlad774/vprokube/blob/main/running_kuber.png)
 ![First try](https://github.com/Vlad774/vprokube/blob/main/load_balancer.png)
 ![First try](https://github.com/Vlad774/vprokube/blob/main/service_running.png)
