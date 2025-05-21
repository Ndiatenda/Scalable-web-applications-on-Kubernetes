# Scalable web applications on Kubernetes
-----------------------------------------------
This course goes through how to scaffold a web application, run it locally in a container, and then deploy it to a Kubernetes cluster created with Kubernetes Service.

## Objectives: 
* Scaffold a statter Application
* Deploy the application on the Kubernetes cluster.
*  Bind a custom domain.
* Monitor the logs and health of the cluster.
* Scale Kubernetes pods.

## Architecture
1. A developer generates an application with Cloud Developer Tools.
2. Building the application produces a Docker container image.
3. The image is pushed to a namespace in kubernetes service.
4. The application is then deployed to a kubernetes cluster where users  
