# Task 3 – Kubernetes Deployment

## Objective

The objective of this task is to deploy a containerized application using Kubernetes and understand how deployments and services work in a container orchestration environment.

---

## Overview of Kubernetes

Kubernetes is an open-source container orchestration platform used to automate deployment, scaling, and management of containerized applications.

Key components used in this task:

- Deployment
- Pods
- Service

---

## Application Description

A simple web application is deployed using the NGINX container image.

- Container Image: nginx
- Number of replicas: 2
- Container Port: 80

---

## Kubernetes Deployment

The deployment configuration defines:

- Number of pod replicas
- Container image
- Pod labels
- Port configuration

The deployment ensures high availability by running multiple replicas of the application.

---

## Kubernetes Service

A NodePort service is used to expose the application.

Service details:

- Type: NodePort
- Port: 80
- NodePort: 30007

This allows external access to the application through the node’s IP address.

---

## Deployment Process

1. Kubernetes deployment YAML creates application pods.
2. Service YAML exposes the pods externally.
3. Kubernetes manages scaling and availability.

---

## Tools and Technologies Used

- Kubernetes
- Docker (container image)
- YAML configuration files

---

## Outcome

- Successfully defined Kubernetes deployment and service.
- Demonstrated container orchestration using Kubernetes.
- Understood pod management and service exposure.

---

## Conclusion

This task demonstrates the basic concepts of Kubernetes deployment and service configuration. It highlights how Kubernetes manages containerized applications efficiently and ensures scalability and availability.
