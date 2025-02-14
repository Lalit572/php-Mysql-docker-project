**Title - Deploying a Scalable PHP-MySQL Web Application on AWS EKS with ECR and EC2**

**Project Description: -**

This project demonstrates the deployment of a scalable PHP-MySQL-based Visitor Management System on Amazon EKS (Elastic Kubernetes Service) using AWS ECR (Elastic Container Registry)
for container image management and EC2 instances as worker nodes for the Kubernetes cluster. The project showcases how to containerize, orchestrate, and deploy a web application while
leveraging the managed services of AWS for high availability, scalability, and reliability.

**Key Features-**

Containerization:
The PHP application and MySQL database are containerized using Docker.

Elastic Kubernetes Service (EKS):
AWS EKS is used to manage and orchestrate the deployment of containers.

Elastic Container Registry (ECR):
Docker images for the PHP application and MySQL database are stored securely in AWS ECR.

EC2 as Worker Nodes:
EC2 instances serve as worker nodes for the EKS cluster, providing the computational resources needed to run the containers.

MySQL Database Integration:
MySQL is deployed as a containerized service within the cluster.

Docker Compose for Local Development:
Docker Compose is used for local multi-container testing of the PHP application and MySQL database before deploying to EKS.

Load Balancing:
The PHP application is exposed to the internet via a Kubernetes LoadBalancer service, ensuring traffic is distributed across multiple replicas.

Scalability and Reliability:
Kubernetes ensures high availability of the application by deploying multiple replicas of the PHP application.

**Workflow Overview-**

Development and Containerization:

Pushing Images to ECR:

Kubernetes Configuration:
Define Kubernetes YAML files for PHP and MySQL deployments.

Deployment on EKS:
Set up an EKS cluster with EC2 worker nodes.

Access and Monitoring:
Access the application via the LoadBalancer service's external IP.

**Benifits-**

Scalability,High Availability,Security,Flexibility
