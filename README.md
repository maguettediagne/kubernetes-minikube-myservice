\# TP Kubernetes – Minikube (MyService)



\## Image Docker Hub

https://hub.docker.com/r/maguettediagne/myservice



\## Description

Déploiement d’un service web Java conteneurisé avec Docker

et orchestré avec Kubernetes via Minikube.



\## Fichiers Kubernetes

\- deployment.yml

\- service-nodeport.yml

\- service-loadbalancer.yml

\- ingress.yml



\## Commandes principales

```bash

kubectl apply -f deployment.yml

kubectl apply -f service-nodeport.yml

kubectl apply -f ingress.yml



