🚀 MongoDB + WebApp Deployment on Kubernetes
This project demonstrates deploying a simple web application connected to a MongoDB database using Kubernetes. It includes proper use of Secrets, ConfigMaps, Deployments, and Services.

📁 Project Structure
mongo-secret.yaml – Stores MongoDB credentials using Kubernetes Secrets.

mongo-config.yaml – Stores the MongoDB service URL via ConfigMap.

mongo.yaml – Deploys MongoDB and exposes it via ClusterIP service.

webapp.yaml – Deploys the web application and exposes it via NodePort service.

