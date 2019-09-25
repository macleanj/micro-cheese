# Micro Cheese
This GIT repo and image is used to test micro-services in Kubernetes. Every page is used as a separate service/Pod and can scale its resources individually.

# How it works
The docker image created includes the main html page displaying yummy Dutch cheeses (yes, I'm Dutch). From there you can select the cheese of your favorite. It is up to you to map the individual routes onto routes or hosts going to individual micro-services in Kubernetes.

Assumptions:
- Name resolution (/etc/hosts works will work with kind and minikube)
- Careful with rewrite in the ingress controller annotations. This might break pictures.

