# k8s-server
Kubernetes manifests for the Deployment, Service, and Ingress to run an NGINX server
# NGINX Kubernetes Deployment

This repository contains the Kubernetes manifests to deploy an NGINX server, along with the associated Service and Ingress resources.

## Files

- `nginx-deployment.yml`: Contains the Deployment, Service, and Ingress configurations for the NGINX server.

## Usage

To deploy the NGINX server, apply the `nginx-deploymrnt.yml` file:

```cmd to apply 
kubectl apply -f nginx-deployment.yml
