# Jenkins-Docker-Kubernetes
This Repo contains of Tomcat Source Code 
I Created Jenkinsfile,Deployment.yaml and ServiceLb.yaml
The Jenkinsfile is used for CI CD Puropse where it is used for building the docker image and pushing to dockerhub
After that image got pulled and deployed to GKE
Deployment.yaml is for the creation of pods and servicelb.yaml is used for networking.These both yaml files are deployed in GKE
