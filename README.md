# kubernetes-first-demo
My first demo project with Kubernetes

Using "Minikube" to run this project on local environment.

Install Minikube using the following steps:


Main Kubernetes commands:

#To create a pod from yaml file use the following command
kubectl apply -f <YAML_FILENAME>

#example:
kubectl apply -f mongo.yaml

#To get the list of pods running in the cluster:
kubectl get pod
