# 🚀 Core AWS Services — Compute

Compute services in AWS allow you to **run applications and workloads** in the cloud with flexible options based on your needs.

---

## 🖥️ Amazon EC2 — Elastic Compute Cloud
- Virtual servers in the cloud
- Full control of OS, CPU, storage, networking
- Multiple instance types for different workloads
- Pricing models: On-Demand, Reserved, Spot

🔹 Best for: Web apps, databases, legacy app migration

---

## ⚡ AWS Lambda — Serverless Compute
- Run code **without** managing servers
- Scales automatically with demand
- Pay only for execution time

🔹 Best for: Automation, event-driven apps, microservices

---

## 🧩 Amazon ECS — Elastic Container Service
- Run & manage Docker containers
- Works with EC2 or Fargate

🔹 Best for: Microservices using Docker containers

---

## ☸️ Amazon EKS — Elastic Kubernetes Service
- Fully managed Kubernetes service
- Scales containerized workloads globally

🔹 Best for: Modern container applications using Kubernetes

---

## 🚀 AWS Fargate — Serverless Containers
- Run containers **without** managing EC2 instances
- Secure and fully managed autoscaling

🔹 Best for: Simple + scalable container workloads

---

## 🆚 Quick Comparison of Compute Services

| Service | Type | Who Manages Servers? | Best For |
|--------|------|---------------------|----------|
| EC2 | Virtual Machines | You | Full control applications |
| Lambda | Serverless Functions | AWS | Event-driven workloads |
| ECS | Container Orchestration | Shared | Microservices using Docker |
| EKS | Kubernetes Orchestration | Shared | Enterprise-level scaling |
| Fargate | Serverless Containers | AWS | Simplified container workloads |

---

### 📌 Interview Tip
> EC2 gives maximum control. Lambda and Fargate handle servers automatically.

---

### 🧠 Summary
AWS Compute services provide:
- Flexibility (EC2)
- Serverless simplicity (Lambda, Fargate)
- Scalable container orchestration (ECS, EKS)

Your choice depends on:
➡ Level of control  
➡ Application architecture  
➡ Cost & scaling requirements  
