# Prometheus Monitoring Setup  
## Prometheus & Node Exporter Installation Guide  

This repository provides clear, step-by-step instructions for deploying a basic monitoring stack using **Prometheus** and **Node Exporter**. It’s designed to help you easily set up and monitor your system’s performance metrics.  

---

##  Prerequisites  

Before starting, make sure you have the following:  

- Access to a **Linux-based** machine (physical, virtual, or cloud instance).  
- In this setup, an **AWS EC2 instance** is used with:  
  - **Operating System:** Ubuntu  
  - **Security Group Configuration:**  
    - Open **port 9090** → for Prometheus  
    - Open **port 9100** → for Node Exporter  

---
