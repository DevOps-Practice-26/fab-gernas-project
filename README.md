# 🚀 Spring Boot Application Deployment on Kubernetes

## 📖 Project Overview

This project demonstrates how to deploy a Spring Boot application with MongoDB on a Kubernetes cluster.

The application is containerized using Docker and deployed using Kubernetes resources such as Deployments, Services, ConfigMaps, Secrets, Persistent Volumes, and Ingress.

---

## 🛠 Technologies Used

- Java 17
- Spring Boot
- MongoDB
- Docker
- Kubernetes
- Git & GitHub
- Jenkins
- AWS EKS

---

## 📂 Project Structure

```
project/
│
├── deployment.yaml
├── service.yaml
├── configmap.yaml
├── secret.yaml
├── ingress.yaml
├── pvc.yaml
├── Dockerfile
├── pom.xml
└── README.md
```

---

## 🚀 Prerequisites

Before running this project, make sure you have:

- Docker
- Kubernetes Cluster
- kubectl
- Git
- Java 17
- Maven

---

## 📥 Clone Repository

```bash
git clone https://github.com/yourusername/springboot-k8s.git
```

Move into the project directory:

```bash
cd springboot-k8s
```

---

## 🐳 Build Docker Image

```bash
docker build -t springapp:v1 .
```

---

## ☸ Deploy to Kubernetes

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f configmap.yaml
kubectl apply -f secret.yaml
```

---

## 🔍 Verify Resources

```bash
kubectl get pods

kubectl get svc

kubectl get deploy
```

---

## 🌐 Access Application

```
http://<NodeIP>:<NodePort>
```

or

```
http://your-domain.com
```

---

## 📦 Features

- Dockerized application
- Kubernetes Deployment
- ConfigMap support
- Secret management
- MongoDB Integration
- Persistent Storage
- Ingress Support
- Rolling Updates

---

## 👨‍💻 Author

**Vamsi Krishna**

GitHub: https://github.com/vamsikrish2208

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ If you like this project

Please give it a ⭐ on GitHub.
