# EC2 Instance Types & Pricing Explained

EC2 (Elastic Compute Cloud) provides virtual servers in AWS to run applications.  
Choosing the right **instance type** and **pricing model** is important for cost-optimization and performance.

---

## 🧩 EC2 Instance Type Categories

| Instance Type | Optimized For | Example Use Cases |
|--------------|---------------|------------------|
| **t**, **a**, **m** series | General Purpose | Web apps, Dev/QA environments |
| **c** series | Compute Optimized | High-performance CPU workloads, gaming servers |
| **r**, **d**, **z** series | Memory Optimized | Databases, real-time analytics |
| **p**, **g** series | GPU Accelerated | AI/ML, graphics processing |
| **i** series | Storage Optimized | High-IOPS databases, NoSQL |
| **h**, **d** series | Disk Throughput Optimized | Big Data, Hadoop workloads |

> 💡 Tip: Start with **t2.micro or t3.micro** (Free Tier eligible)

---

## 💰 EC2 Pricing Models

| Pricing Model | When to Use | Cost Benefit |
|--------------|-------------|--------------|
| **On-Demand** | Short-term projects | Most expensive but flexible |
| **Reserved Instances (RI)** | Long term (1–3 years) predictable workloads | Up to **72%** savings |
| **Spot Instances** | Fault-tolerant workloads | **Up to 90%** cheaper |
| **Savings Plans** | Long term with some flexibility | Cheaper than on-demand |
| **Dedicated Hosts** | Compliance, licensing restrictions | Very expensive |

---

## 📌 Key Concepts

- **vCPU** → Virtual CPU running inside the instance  
- **RAM** → Memory used for application data  
- **EBS** → Persistent block storage  
- **Network Performance** → from Low → 100Gbps  

---

## 🎯 Common Interview Questions

1. What is the difference between **On-Demand** and **Reserved Instances**?
2. Which instance types are best for memory-intensive applications?
3. How Spot Instances reduce cost?
4. What is the Free Tier instance type?

Practice answering these — they come a lot!

---

## 📘 Hands-On I Completed

✔ Launched **t2.micro Ubuntu EC2**  
✔ Installed web server and hosted webpage  
✔ Created a backend Node.js API  
✔ Managed cost using Free Tier  

---

> 🚀 This topic is very important for AWS Solutions Architect & Cloud Engineer roles.  
Next: Learn **EC2 Security Groups & Key Pairs** 🔐
