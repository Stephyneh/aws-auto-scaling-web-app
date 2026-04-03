# 🚀 Scalable Web Application on AWS

## 📌 Overview
This project demonstrates how to design and deploy a scalable and highly available web application using AWS cloud services.

The system automatically adjusts resources based on traffic demand, ensuring performance and cost efficiency.

---

## 🧰 Technologies Used
- Amazon Web Services (AWS)
- EC2 (Elastic Compute Cloud)
- Auto Scaling Group
- Application Load Balancer
- Security Groups

---

## 🏗️ Architecture
- Application Load Balancer distributes incoming traffic
- Auto Scaling Group dynamically adjusts the number of EC2 instances
- EC2 instances run a web server configured via user data script

---

## ⚙️ Features
- High availability across multiple Availability Zones
- Automatic scaling based on demand
- Fault tolerance
- Cost optimization

---

## 🚀 Deployment Steps
1. Created a Security Group allowing HTTP and SSH access
2. Configured a Launch Template with user data to install a web server
3. Created a Target Group and Application Load Balancer
4. Set up an Auto Scaling Group using the launch template
5. Configured scaling policies and scheduled actions

---

## 📸 Screenshots


## 📈 Real-World Use Case
This architecture is used by modern cloud applications to handle variable traffic loads efficiently, similar to systems used by companies like Netflix and Amazon.

---

## 📚 What I Learned
- Cloud infrastructure design on AWS
- Load balancing and traffic distribution
- Auto Scaling for performance and cost efficiency
- High availability best practices

---

## 🔗 Author
Stephany
