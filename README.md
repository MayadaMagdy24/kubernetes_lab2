# kubernetes_lab2
 Kubectl config:
Create a k3s cluster with 1 server (controlplane) and 1 agent (worker)

In your cluster create a new namespace called iti-43.

Edit the kubectl config file to add a new context that uses the default user with the new namespace you just created. 

 Kubectl plugin:
Create a new kubectl plugin called “kubectl hostnames” that should display the hostnames of all your nodes on the cluster

- Creating deployments
Create a deployment YAML file that has 3 replicas of image “nginx:alpine”
