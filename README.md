# 🌐 Highly Available WordPress Web Application on AWS  

## 📌 Overview  

This project demonstrates how to deploy a **highly available, scalable, and resilient WordPress application** on AWS. By leveraging **Amazon VPC, EC2, RDS, EFS, and ALB**, the architecture ensures **high uptime, scalability, and fault tolerance**, making it ideal for high-traffic WordPress sites.  

## 🏗 Architecture  

- **Amazon VPC** – Isolated network environment.  
- **Amazon RDS** – Managed MySQL database with high availability.  
- **Amazon EFS** – Shared file storage across multiple EC2 instances.  
- **Amazon EC2** – Hosts WordPress instances with Auto Scaling.  
- **Application Load Balancer (ALB)** – Distributes traffic efficiently.  

## 🚀 Deployment Steps  

1. **Set Up Networking** – Configure VPC, subnets, Internet Gateway, and security groups.  
2. **Deploy RDS (MySQL)** – Create a multi-AZ database for WordPress.  
3. **Configure EFS** – Set up shared storage for WordPress media.  
4. **Launch EC2 Instances** – Deploy WordPress with Auto Scaling and attach EFS.  
5. **Set Up ALB** – Route traffic to healthy instances dynamically.  
6. **Finalize & Test** – Verify high availability and failover handling.  

## ⚡ Key Benefits  

✅ **Auto Scaling** – Dynamically adjusts to traffic spikes.  
✅ **Fault Tolerance** – Ensures minimal downtime with multi-AZ deployment.  
✅ **Cost Optimization** – Uses AWS-managed services to reduce maintenance overhead.  

## 🔧 Challenges & Solutions  

- **Database Connection Issues** → Fixed by adjusting VPC security groups.  
- **File Synchronization** → Resolved using **Amazon EFS** for shared storage.  

## 📜 Conclusion  

This project demonstrates how **AWS infrastructure** can be used to **deploy a production-ready WordPress application** with high availability and scalability. Ideal for **e-commerce, news platforms, and corporate sites** requiring **zero-downtime** and **auto-recovery**.

---

💡 **Happy Hosting!** 🚀
