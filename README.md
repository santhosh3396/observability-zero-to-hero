# 🚀 7-Day Observability Project (Production-Ready)

## 📌 Overview

This project demonstrates how to build a **production-grade observability platform** on Kubernetes (AWS EKS).

It includes:

* Metrics (Prometheus)
* Visualization (Grafana)
* Logging (ELK Stack)
* Tracing (Jaeger & OpenTelemetry)

---

## 🛠 Tech Stack

* AWS (EKS, EC2, VPC, IAM)
* Kubernetes
* Terraform (Infrastructure as Code)
* Helm
* Prometheus & Grafana
* ELK Stack (Elasticsearch, Fluentbit, Kibana)
* Jaeger & OpenTelemetry
* CI/CD (Jenkins / GitHub Actions)

---

## 📁 Project Structure

```
day-1 → Observability basics  
day-2 → Prometheus setup  
day-3 → Grafana dashboards  
day-4 → Logging (ELK Stack)  
day-5 → Distributed tracing (Jaeger)  
day-6 → OpenTelemetry  
day-7 → Production best practices  
```

---

## ⚙️ Setup Instructions

### Step 1: Clone Repository

```
git clone <your-repo-url>
```

### Step 2: Create EKS Cluster (Terraform)

```
cd terraform
terraform init
terraform apply
```

### Step 3: Install Helm

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
```

### Step 4: Deploy Monitoring Stack

```
helm install prometheus prometheus-community/kube-prometheus-stack
```

### Step 5: Setup Logging (ELK)

* Deploy Fluentbit
* Connect to Elasticsearch
* Visualize in Kibana

### Step 6: Setup Tracing

* Deploy Jaeger
* Integrate OpenTelemetry

---

## 🔥 Production Features

* Infrastructure as Code using Terraform
* Centralized logging system
* Distributed tracing
* Real-time monitoring dashboards
* Scalable Kubernetes architecture
* CI/CD pipeline ready

---

## 💼 Use Case

This project helps teams:

* Monitor microservices in real-time
* Troubleshoot issues using logs
* Trace requests across services
* Improve system reliability

---

## 📊 Screenshots (Add later)

* Grafana Dashboard
* Kibana Logs
* Jaeger Tracing

---

## 👨‍💻 Author

Santosh Kuldeepalli
