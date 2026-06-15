# Dockerized CRM Platform

## Project Overview

This project demonstrates the deployment of a full-stack CRM (Customer Relationship Management) platform using modern DevOps practices.

The application consists of:

* React Frontend
* Node.js Backend API
* MongoDB Database

The solution was containerized using Docker, orchestrated using Docker Compose, deployed to Kubernetes, and packaged using Helm.

---

## Architecture

Frontend (React)
↓
Backend API (Node.js)
↓
MongoDB

CI/CD Pipeline:
GitHub → GitHub Actions → Docker Build

Deployment Options:
Docker Compose
Kubernetes Deployments & Services
Helm Chart

---

## Technologies Used

### Frontend

* React

### Backend

* Node.js
* Express

### Database

* MongoDB

### DevOps

* Docker
* Docker Compose
* Kubernetes
* Helm
* GitHub Actions
* Git
* Linux

---

## Key Features

* Multi-container architecture
* Container networking
* Kubernetes deployment
* Helm chart packaging
* CI/CD automation using GitHub Actions
* Mobile and desktop accessibility

---

## Challenges Solved

### MongoDB Connectivity

Issue:
Backend failed to connect to MongoDB.

Error:
ENOTFOUND mongo

Resolution:
Added MongoDB service to Docker Compose and configured service discovery.

### React Runtime Compatibility

Issue:
ERR_OSSL_EVP_UNSUPPORTED

Resolution:
Migrated frontend image from Node 18 to Node 16.

### Kubernetes Image Pull Issues

Issue:
ErrImageNeverPull

Resolution:
Updated image pull configuration and validated image availability.

---

## Learning Outcomes

* Docker containerization
* Docker Compose orchestration
* Kubernetes Deployments
* Kubernetes Services
* Helm chart management
* GitHub Actions CI/CD
* Application troubleshooting

---

## Author
Anil Ediga

