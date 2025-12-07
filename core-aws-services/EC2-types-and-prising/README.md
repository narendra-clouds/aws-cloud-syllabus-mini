# EC2 — Instance Types & Pricing

## 📦 What is EC2

Amazon EC2 (Elastic Compute Cloud) is AWS’s virtual server service: you rent virtual machines (“instances”) rather than managing physical hardware. You get flexibility, scalability, and pay-as-you-go billing.  

---

## 🧰 EC2 Instance Types (Overview)

AWS offers many instance types, optimized for different workloads. Common families include:

| Instance Family | Purpose / Workload Type |
|-----------------|-------------------------|
| **General Purpose** (e.g. t2, t3, t4g, m5, m6g) | Balanced CPU, memory, cost — good for web apps, small-medium servers, dev environments. |
| **Compute Optimized** (e.g. c5, c6g) | High CPU / compute power — good for compute-heavy workloads, batch processing, scientific computing. |
| **Memory Optimized** (e.g. r5, r6g, x1e) | High memory — good for large in-memory databases, caching, big data processing. |
| **Storage / I/O Optimized** (e.g. i3, i3en, d2) | High disk/IO performance — good for databases, data-intensive workloads, high read/write. |
| **GPU / Accelerated Compute** (e.g. p3, g4, g5) | GPU-enabled — for machine learning, graphics, video rendering, AI workloads. |
| **Burstable / Low-cost** (e.g. t2, t3, t4g) | Low-cost instances that can “burst” CPU — good for light workloads, learning, development, small apps. |

> ✅ Tip: For learning, small projects or proof-of-concept — use **t2 / t3 / t4g** (free-tier / low cost).  
> ✅ For production or real workloads — choose based on need: CPU-heavy → compute-optimized; Memory-heavy → memory-optimized; etc.

---

## 💲 EC2 Pricing Models  

AWS offers different pricing/payment models for EC2. Common ones:

| Pricing Type | Description |
|--------------|-------------|
| **On-Demand** | Pay per hour/second (depending on region) for your usage. No long-term commitment. Flexible. |
| **Reserved Instances / Savings Plans** | Commit for 1 or 3 years; pay lower hourly rate. Good if instance runs long-term. |
| **Spot Instances** | Use spare AWS capacity at huge discounts — but AWS can reclaim at any time. Good for fault-tolerant or batch jobs. |
| **Free Tier (for new AWS accounts)** | Limited free usage (e.g. t2.micro / t3.micro up to certain hours per month) — ideal for learning & testing. |
| **Dedicated Hosts / Dedicated Instances** | Dedicated physical hardware for compliance or licensing — higher cost, niche use cases. |

---

## 🧮 What You Should Do (as Learner / Developer)

- Always check instance type you select — cost vs performance trade-off.  
- For small personal projects / learning → use free-tier eligible or low-cost general-purpose instances (t2, t3).  
- For long-term or production → evaluate Reserved / Savings Plans to save money.  
- For flexible workloads or batch jobs → Spot Instances can drastically reduce cost.  
- Always stop or terminate instances when not needed — EC2 billing continues until you stop/terminate.

---

## 📌 Example — Cost Comparison (Hypothetical)

| Use Case | Suggested Instance Type | Pricing Model |
|---------|--------------------------|---------------|
| Learning / testing small web app | t3.micro (free-tier) | On-Demand / Free-Tier |
| Medium web app / server | t3.medium / m5.large | On-Demand or Savings Plan (if long run) |
| Data processing / compute heavy task | c5.large / c6g.large | On-Demand or Spot (if non-critical) |
| Large database / in-memory cache | r5.large / r6g.large | On-Demand / Reserved (long run) |

---

## 📚 Tips for Cost Management & Best Practices

- Use AWS Free Tier or always track usage on dashboard.  
- Clean up unused resources (stop/terminate EC2 when not in use).  
- Use Spot + Auto-scaling for cost-efficient workloads.  
- Monitor instance usage via CloudWatch → avoid over-provisioning.  
- For predictable workloads → use Savings Plans / Reserved instances to reduce cost.

---

## 🔗 Useful AWS Documentation & References

- Official AWS EC2 Pricing: https://aws.amazon.com/ec2/pricing/  
- EC2 Instance Types: https://aws.amazon.com/ec2/instance-types/  
- AWS Free Tier Details: https://aws.amazon.com/free/  

---

*Document created by Narendra — part of my AWS Cloud Syllabus journey.*  
