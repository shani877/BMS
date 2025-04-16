# 🚀 **DevOps Project: Book My Show App Deployment**

Welcome to the **Book My Show App Deployment** project! This project demonstrates how to deploy a **Book My Show-clone application** using modern DevOps tools and practices, following a **DevSecOps** approach.

---

## 🛠️ **Tools & Services Used**

| **Category**         | **Tools**                                                                                                                                                                                                 |
|----------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Version Control**  | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)                                                                                                       |
| **CI/CD**            | ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)                                                                                                    |
| **Code Quality**     | ![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)                                                                                              |
| **Containerization** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)                                                                                                       |
| **Orchestration**    | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)                                                                                           |
| **Monitoring**       | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Security**         | ![OWASP](https://img.shields.io/badge/OWASP-000000?style=flat-square&logo=owasp&logoColor=white) ![Trivy](https://img.shields.io/badge/Trivy-00979D?style=flat-square&logo=trivy&logoColor=white)         |

---

## ⚙️ **Tool Installation**

To set up your environment with all the necessary tools, follow these steps:

```bash
# Clone the repository
git clone https://github.com/shani877/Scripts.git

# Navigate to the repository directory
cd Scripts

# Execute each tool installation script
bash awscli.sh
bash docker.sh
bash eksctl.sh
bash helm.sh
bash jenkins.sh
bash kubectl.sh
bash sonarqube.sh
bash trivy.sh
```

> ✅ Make sure each `.sh` script has executable permissions. If not, run `chmod +x *.sh` before executing.

---

## 🚦 **Project Stages**

### ✅ Phase 1: Deployment to Docker Container
- Containerize the application using Docker.
- Build and push Docker images to a container registry.
- Run the application in a Docker container.

### ✅ Phase 2: Deployment to EKS Cluster with Monitoring
- Deploy the application to an **Amazon EKS (Elastic Kubernetes Service)** cluster.
- Set up **Prometheus** and **Grafana** for monitoring and visualization.
- Implement **Trivy** for vulnerability scanning and **OWASP** for security best practices.

---

## 📂 **Code Repository**

Explore the code and contribute to the project:  
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/shani877/BMS.git)

---

## 📹 **Project Video**

Watch the step-by-step deployment process:  
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/hBGVwa8MY4A)

---

## 🎉 **Happy Learning!**
