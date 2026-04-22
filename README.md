# Cloud Native System Monitor 🚀

A real-time system monitoring application built with Python, Flask, Docker, and Kubernetes. Deployed on AWS ECR and ECS.

## 📊 Features
- Real-time CPU monitoring
- Real-time Memory monitoring
- Beautiful Plotly gauge charts
- Alert system when usage exceeds 80%
- Containerized with Docker
- Deployed on Kubernetes

## 🛠️ Tech Stack
- **Python & Flask** - Backend web framework
- **Plotly** - Interactive gauge charts
- **Docker** - Containerization
- **Kubernetes** - Container orchestration
- **AWS ECR** - Container registry
- **AWS ECS** - Container deployment

## 🚀 How to Run

### Using Docker
```bash
docker build -t my-flask-app .
docker run -p 5000:5000 my-flask-app
```

### Using Kubernetes
```bash
kubectl apply -f deployment.yaml
kubectl port-forward service/flask-service 5000:80
```

Then open: http://localhost:5000

## 📁 Project Structure
