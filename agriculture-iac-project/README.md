\# IaC Provisioning for Agriculture System



\## Description

This project demonstrates Infrastructure as Code (IaC) by deploying a dummy agriculture web application using Docker and Kubernetes.



\## Tools Used

\- Git

\- Docker

\- Kubernetes

\- Nginx



\## How It Works

1\. Docker builds an image of the agriculture app.

2\. Kubernetes deploys the container as pods.

3\. Service exposes the app using NodePort.



\## How to Run

docker build -t agri-app .

kubectl apply -f k8s/deployment.yaml

kubectl get pods

kubectl get svc



\## CI/CD (Conceptual)
In real-world usage, this project can be integrated with Jenkins or GitHub Actions to automatically build Docker images and deploy to Kubernetes on every code change.

