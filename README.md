# *End-to-End DevSecOps Kubernetes Project: Including DevSecOps, GitOps, Monitoring for Site Reliability*


## Tools: 

**Cloud Infrastructure Setup:**
- AWS (IAM, EKS, ALB, Route53, CLI, etc)
- Terraform (Infrastructure As Code)

**Continuous integration & Continuous Deployment:**
- Github Actions (CI/CD pipeline/workflow)
- ArgoCD for continuous delivery and GitOps

**SECURITY:** (SAST/SCA) Scanning:
 - Sonarqube (Code quality analysis through SAST Scanning)
 - Snyk (Vulnerability scanning and dependency management analysis)
 - Trivy (Filesystem and Container image vulnerability scanning)

**Container/Container Orchestration:**
- Docker/Dockerhub (Containerization + storing backend and frontend as Docker Images)
- Kubernetes (Container Orchestration)
- Helm (installations and deployments)

**Monitoring:**
- Prometheus (Collected metrics from clusters, pods etc)
- Grafana (Visualise data/analytics from prometheus using dashbaords)

# PROJECT:

## Terraform Configuration:
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/08efd049-6bb1-4f7d-bf5e-70a0033a7e2d)

## Github Actions CI/CD Pipeline:
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/0c03cd97-1072-420f-a8b3-d92c80dc305b)
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/3437324c-08f5-450c-a2b7-d65797e55414)


## ArgoCD:
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/18e93b51-4d56-4a69-a18d-e69752234f86)

## SECURITY: SonarQube
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/069c012f-7404-4621-994b-deb0abf48b15)

## SECURITY: Snyk
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/8351d170-fb5d-4d11-99ea-e037c3f44f62)

## Working Application:
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/ece97ea3-b3b5-47fd-8559-f6a60c40530f)
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/d756eb99-d43d-422e-857b-0f547c68b8ee)

## Working Services:
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/6c9b492b-4960-4bb7-b1a5-7f24959a9ba5)

## Monitoring: Prometheus
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/f9a187f1-8c2b-4948-be96-40d0129ddce2)

## Monitoring: Grafana
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/91f6f691-577e-4eb1-aeaf-4421b4c01138)
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/db6e0e4e-233f-4dfb-9620-6e7209954c96)

## AWS: Route53 DNS A Record
![image](https://github.com/CloudHirsi/AWS-K8-CICD/assets/153539293/9c887ac5-3ff5-4a9a-bef5-3f3be3163cfb)

# *PROJECT SUMMARY*

As part of my *"End-to-End DevSecOps Kubernetes Project,"* I undertook the task of developing a robust and secure containerized application infrastructure on AWS. This project aimed to leverage Kubernetes for container orchestration while implementing industry best practices for security and continuous integration/continuous deployment (CI/CD).

## **Task:**
To accomplish this, I identified the need for a comprehensive set of tools and technologies to ensure the security and reliability of the infrastructure and application deployments. My task involved selecting and integrating various tools into the project workflow to address key areas such as cloud provisioning, security scanning, containerization, container orchestration, and monitoring.

## **Evaluation:**

## *Cloud Infrastructure Setup:*
**AWS:**
- By leveraging AWS services such as IAM, EKS (Elastic Kubernetes Service), ALB (Application Load Balancer), Route53, the AWS CLI and more, I provisioned the necessary cloud resources to support the Kubernetes cluster and application deployments.

**Terraform (Infrastructure As Code):**
- I utilized Terraform for implementing Infrastructure as Code (IaC) principles, enabling the automated provisioning and management of AWS cloud resources in a consistent and reproducible manner.

## *Continuous Integration & Continuous Deployment (CI/CD) Pipeline:*
**Github Actions:**
- Using Github Actions, I configured a CI/CD pipeline to automate the build, test, and deployment processes for the application codebase.
  
**ArgoCD:**
- Additionally, I implemented ArgoCD for continuous delivery and GitOps practices, ensuring consistent and reliable deployments across environments.

## *Security Scanning with SAST/SCA Tools:*

**Sonarqube:**
- Integrated Sonarqube for static application security testing (SAST), enabling code quality analysis and identification of potential vulnerabilities and code smells.
  
**Snyk:**
- Implemented Snyk for vulnerability scanning and dependency management analysis, ensuring that the project's dependencies were free from known security vulnerabilities.

**Trivy:**
- Utilized Trivy for filesystem and container image vulnerability scanning, providing proactive identification and remediation of security issues in containerized environments.

## *Containerization and Container Orchestration:*

**Docker/Dockerhub:**
- Leveraged Docker for containerization and created Docker images for the project's backend and frontend components. Utilized Dockerhub for storing and managing the Docker images.

**Kubernetes:**
- Deployed the containerized application on Kubernetes, leveraging its robust container orchestration capabilities for managing and scaling application workloads.

**Helm:**
- Utilized Helm for package management and simplifying the installation and deployment of Kubernetes applications, including the project's microservices.

## *Monitoring and Analytics:*

**Prometheus:** 
- Implemented Prometheus for collecting metrics from Kubernetes clusters, pods, and other resources, enabling real-time monitoring and alerting.

**Grafana:**
- Integrated Grafana for visualizing data and analytics from Prometheus using custom dashboards, providing insights into the performance and health of the infrastructure and applications.

## **Results:**
Through my effective selection and integration of these tools and technologies, my *"End-to-End DevSecOps Kubernetes Project"* successfully achieved its objectives of establishing a secure, scalable, and automated containerized application infrastructure on AWS. My implementation of industry best practices through robust security measures, CI/CD automation, GitOps, containerization, container orchestration, and monitoring capabilities laid the foundation for reliable and efficient application deployment and management in a cloud-native environment.















