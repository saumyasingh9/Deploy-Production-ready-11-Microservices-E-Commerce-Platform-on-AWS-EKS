## 🛒 **End to end deployement of 11 Microservices E-Commerce Application on AWS EKS**
Read my Project Blog here https://saumyasingh.hashnode.dev/deploying-a-full-microservices-e-commerce-application-on-aws-eks

### Overview

This project demonstrates the **end-to-end deployment of a production-grade Microservices-based E-Commerce Platform** on **Amazon Elastic Kubernetes Service (EKS)** using **Terraform, Jenkins, ArgoCD, Docker, Prometheus, and Grafana**.
It includes **11 microservices**, **automated CI/CD pipelines**, **GitOps with ArgoCD**, **infrastructure-as-code (IaC)**, and **real-time monitoring** — all deployed securely on AWS.
![alt text](<microservices project.webp>)

---

## 🧩 **Architecture Overview**

**Key Components:**

* **Frontend Service** (React)
* **Backend Microservices (10)**:
  `emailservice`, `checkoutservice`, `recommendationservice`, `paymentservice`,
  `productcatalogservice`, `cartservice`, `currencyservice`, `shippingservice`,
  `adservice`, `loadgenerator`
* **Infrastructure**: AWS EKS, EC2 JumpHost, Terraform-managed networking & ECR
* **CI/CD**: Jenkins Pipelines for automation
* **GitOps**: ArgoCD for continuous deployment
* **Monitoring**: Prometheus & Grafana for metrics and dashboards
* **Security**: HTTPS setup with ACM + Route 53 + Classic Load Balancer

---

## 🧰 **Tech Stack**

| Category                   | Tools Used                                              |
| -------------------------- | ------------------------------------------------------- |
| **Cloud Provider**         | AWS (EKS, EC2, S3, ECR, Route 53, ACM)                  |
| **Infrastructure as Code** | Terraform                                               |
| **CI/CD Automation**       | Jenkins                                                 |
| **Containerization**       | Docker                                                  |
| **Orchestration**          | Kubernetes (EKS)                                        |
| **GitOps Deployment**      | ArgoCD                                                  |
| **Monitoring**             | Prometheus + Grafana                                    |
| **Security & SSL**         | AWS Certificate Manager (ACM)                           |
| **Networking**             | AWS VPC, Subnets, Security Groups                       |
| **Storage**                | S3 for Terraform State, EBS volumes for persistent data |

![alt text](<Screenshot (236).png>)

![alt text](<Screenshot (238).png>)

![alt text](<Screenshot (246).png>)

![alt text](<Screenshot (249).png>)

![alt text](<Screenshot (251).png>)

![alt text](<Screenshot (266).png>)

![alt text](<Screenshot (269).png>)

![alt text](<Screenshot (273).png>)
