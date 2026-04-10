# End-to-End CI/CD Pipeline with Jenkins, Docker, and AWS EC2

This repository demonstrates a complete **CI/CD pipeline** for deploying a Node.js application using Jenkins, Docker, and AWS EC2. The project automates the process from code retrieval to deployment, ensuring **faster releases**, **reliability**, and **scalability**.

---

## Features

- **Automated CI/CD Pipeline**  
  Configured a three-stage Jenkins pipeline:
  1. **Clone**: Retrieves source code from GitHub.
  2. **Build**: Creates a Docker image using a Dockerfile.
  3. **Deploy**: Runs a container with port mapping (3000:3000).

- **Infrastructure Provisioning**  
  Automated setup of AWS EC2 instances using **Terraform** and **Shell scripts**.

- **Scheduled Tasks**  
  Cron jobs implemented for recurring automation tasks.

- **Monitoring & Logging**  
  Logs system performance and resolves issues proactively.

- **Container Orchestration**  
  Kubernetes utilized for scaling and high availability of applications.

---

## Technologies Used

- **AWS EC2** – Cloud virtual machines for deployment.
- **Jenkins** – Automation server for CI/CD pipelines.
- **Docker** – Containerization of applications.
- **GitHub** – Source code repository.
- **Node.js** – Backend application framework.
- **Linux** – Operating system for servers and scripting.
- **Terraform & Shell Scripts** – Infrastructure as Code and automation.
- **Kubernetes** – Container orchestration for scalability.

---

## Project Structure
# End-to-End CI/CD Pipeline with Jenkins, Docker, and AWS EC2

This repository demonstrates a complete **CI/CD pipeline** for deploying a Node.js application using Jenkins, Docker, and AWS EC2. The project automates the process from code retrieval to deployment, ensuring **faster releases**, **reliability**, and **scalability**.

---

## Features

- **Automated CI/CD Pipeline**  
  Configured a three-stage Jenkins pipeline:
  1. **Clone**: Retrieves source code from GitHub.
  2. **Build**: Creates a Docker image using a Dockerfile.
  3. **Deploy**: Runs a container with port mapping (3000:3000).

- **Infrastructure Provisioning**  
  Automated setup of AWS EC2 instances using **Terraform** and **Shell scripts**.

- **Scheduled Tasks**  
  Cron jobs implemented for recurring automation tasks.

- **Monitoring & Logging**  
  Logs system performance and resolves issues proactively.

- **Container Orchestration**  
  Kubernetes utilized for scaling and high availability of applications.

---

## Technologies Used

- **AWS EC2** – Cloud virtual machines for deployment.
- **Jenkins** – Automation server for CI/CD pipelines.
- **Docker** – Containerization of applications.
- **GitHub** – Source code repository.
- **Node.js** – Backend application framework.
- **Linux** – Operating system for servers and scripting.
- **Terraform & Shell Scripts** – Infrastructure as Code and automation.
- **Kubernetes** – Container orchestration for scalability.

---

## Project Structure
# End-to-End CI/CD Pipeline with Jenkins, Docker, and AWS EC2

This repository demonstrates a complete **CI/CD pipeline** for deploying a Node.js application using Jenkins, Docker, and AWS EC2. The project automates the process from code retrieval to deployment, ensuring **faster releases**, **reliability**, and **scalability**.

---

## Features

- **Automated CI/CD Pipeline**  
  Configured a three-stage Jenkins pipeline:
  1. **Clone**: Retrieves source code from GitHub.
  2. **Build**: Creates a Docker image using a Dockerfile.
  3. **Deploy**: Runs a container with port mapping (3000:3000).

- **Infrastructure Provisioning**  
  Automated setup of AWS EC2 instances using **Terraform** and **Shell scripts**.

- **Scheduled Tasks**  
  Cron jobs implemented for recurring automation tasks.

- **Monitoring & Logging**  
  Logs system performance and resolves issues proactively.

- **Container Orchestration**  
  Kubernetes utilized for scaling and high availability of applications.

---

## Technologies Used

- **AWS EC2** – Cloud virtual machines for deployment.
- **Jenkins** – Automation server for CI/CD pipelines.
- **Docker** – Containerization of applications.
- **GitHub** – Source code repository.
- **Node.js** – Backend application framework.
- **Linux** – Operating system for servers and scripting.
- **Terraform & Shell Scripts** – Infrastructure as Code and automation.
- **Kubernetes** – Container orchestration for scalability.

---

## Project Structure
# End-to-End CI/CD Pipeline with Jenkins, Docker, and AWS EC2

This repository demonstrates a complete **CI/CD pipeline** for deploying a Node.js application using Jenkins, Docker, and AWS EC2. The project automates the process from code retrieval to deployment, ensuring **faster releases**, **reliability**, and **scalability**.

---

## Features

- **Automated CI/CD Pipeline**  
  Configured a three-stage Jenkins pipeline:
  1. **Clone**: Retrieves source code from GitHub.
  2. **Build**: Creates a Docker image using a Dockerfile.
  3. **Deploy**: Runs a container with port mapping (3000:3000).

- **Infrastructure Provisioning**  
  Automated setup of AWS EC2 instances using **Terraform** and **Shell scripts**.

- **Scheduled Tasks**  
  Cron jobs implemented for recurring automation tasks.

- **Monitoring & Logging**  
  Logs system performance and resolves issues proactively.

- **Container Orchestration**  
  Kubernetes utilized for scaling and high availability of applications.

---

## Technologies Used

- **AWS EC2** – Cloud virtual machines for deployment.
- **Jenkins** – Automation server for CI/CD pipelines.
- **Docker** – Containerization of applications.
- **GitHub** – Source code repository.
- **Node.js** – Backend application framework.
- **Linux** – Operating system for servers and scripting.
- **Terraform & Shell Scripts** – Infrastructure as Code and automation.
- **Kubernetes** – Container orchestration for scalability.

---

## Project Structure
├── Dockerfile # Docker configuration for the Node.js app
├── Jenkinsfile # Jenkins pipeline definition
├── scripts/ # Shell scripts for automation and provisioning
├── terraform/ # Terraform scripts for EC2 setup
├── src/ # Node.js application source code
└── README.md # Project documentation



---

## Setup & Deployment

1. **Clone Repository**
```bash
git clone https://github.com/Gaurii-git/ci-cd-automation.git
cd ci-cd-automation

Run Jenkins Pipeline
Configure Jenkins with GitHub credentials.
Add the Jenkinsfile to a pipeline job.
Run the pipeline to automatically build, deploy, and start the Node.js container.
Access Application
The app runs on http://<EC2_PUBLIC_IP>:3000.
