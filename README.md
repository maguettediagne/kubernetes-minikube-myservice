# TP Kubernetes – Minikube (MyService)

## Objectif
Déployer une application Java conteneurisée avec Docker sur un cluster Kubernetes local (Minikube),
exposer les services via NodePort et Ingress (API Gateway).

## Architecture
- Deployment myservice (2 pods)
- Deployment myservice2 (1 pod)
- Service Kubernetes myservice (NodePort)
- Service Kubernetes myservice2 (NodePort)
- Ingress NGINX jouant le rôle d’API Gateway

## Image Docker Hub
https://hub.docker.com/r/maguettediagne/myservice

## Déploiement
Les ressources Kubernetes sont décrites à l’aide de fichiers YAML :
- deployment.yml
- service-nodeport.yml
- deployment-myservice2.yml
- service-myservice2.yml
- ingress.yml
