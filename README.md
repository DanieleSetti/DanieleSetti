# Daniele Setti
Junior DevOps Engineer | AWS Cloud & Infrastructure

I design and operate cloud-based systems on AWS, focusing on availability, observability, and failure handling.

I build infrastructure that is not only deployed, but monitored, tested under failure, and recoverable.

---

## 🚀 Projects

### 🔹 Highly Available AWS Infrastructure
https://github.com/DanieleSetti/Highly-Available-Web-Application-Infrastructure-on-AWS

Designed and implemented a production-like AWS architecture:

- Multi-AZ VPC with public/private subnets  
- Application Load Balancer + Auto Scaling Group  
- EC2 instances running Nginx + Node.js  
- RDS (PostgreSQL) in private subnets  
- CI/CD pipeline with GitHub Actions  
- Immutable deployments via instance refresh  
- Secure network isolation (no public EC2/RDS access)  


Focus: building a resilient and scalable application environment.

---

### 🔹 Monitoring & Incident Response System  
https://github.com/DanieleSetti/Monitoring-Incident-Response-System

Built a monitoring system to detect, investigate, and resolve real-world failures in cloud infrastructure:

- Prometheus for metrics collection from EC2 instances (private subnets)  
- Grafana dashboards for CPU, memory, network, and instance health  
- Alerting rules for high CPU usage and instance failures  
- Integration of Node Exporter across Auto Scaling instances  
- Simulated incidents:
  - CPU stress → alert triggered and analyzed  
  - Instance failure → detected via `up == 0`  
  - Service disruption → investigated and resolved  

Focus: understanding system behavior under failure and performing incident response.

---

## 📫 Contact

- LinkedIn: https://www.linkedin.com/in/daniele-kostin-setti  
