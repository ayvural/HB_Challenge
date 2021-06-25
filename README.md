# HB_Challenge
writing a Hello world service on Docker container which is control with kubernetes manifest yaml

# Install minikube and kubectl
https://phoenixnap.com/kb/install-minikube-on-centos

# Hello world service writing with Python language

# Dockerfile built a docker image which is includes your changes, built your container on your local machine.
    ~ docker build -t {username}/helloworld-python .
# If you want to push your container to docker.hub;    
    ~ docker push {username}/helloworld-python
# {username} is your docker.hub username

Manifest file deployment.yaml is doing
    - Deploy the services to k8s clusters
    - Port forwarding
    - Create replicas how many you want to run

# If you want to work this service on your pods you can run the below command
# This is the manifest file for declerative approach
kubectl apply -f deployment.yaml


