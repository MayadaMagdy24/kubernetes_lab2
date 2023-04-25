# kubernetes_lab2
 Kubectl config:
Create a k3s cluster with 1 server (controlplane) and 1 agent (worker)

master:
![Screenshot (1139)](https://user-images.githubusercontent.com/93229250/234342541-80a09f7b-d32e-456d-9ead-cb5899e246ee.png)
worker:
![Screenshot (1140)](https://user-images.githubusercontent.com/93229250/234342571-6d4dfdf9-697e-441a-9626-d10738dfea9c.png)
![Screenshot (1143)](https://user-images.githubusercontent.com/93229250/234343002-a8785964-7ecc-4d32-b816-b9362e719d81.png)

master:
![Screenshot (1144)](https://user-images.githubusercontent.com/93229250/234343245-fa84b02c-862f-4515-95be-b8c14ebfea7a.png)

In your cluster create a new namespace called iti-43.
Edit the kubectl config file to add a new context that uses the default user with the new namespace you just created. 
![Screenshot (1145)](https://user-images.githubusercontent.com/93229250/234343689-0dd07109-6975-483a-9dcd-1de7a0a2e9b1.png)


 Kubectl plugin:
Create a new kubectl plugin called “kubectl hostnames” that should display the hostnames of all your nodes on the cluster
using command : kubectl get nodes | cut -d' ' -f1
![Screenshot (1146)](https://user-images.githubusercontent.com/93229250/234346985-baceb66d-47e1-4d6f-b2af-2ebeff553f8c.png)

- Creating deployments
Create a deployment YAML file that has 3 replicas of image “nginx:alpine”
![Screenshot (1147)](https://user-images.githubusercontent.com/93229250/234347798-3baa6e4b-a16f-4485-afe3-0809cfd20b9b.png)
![Screenshot (1148)](https://user-images.githubusercontent.com/93229250/234348096-5615fa46-def8-4878-b6c9-13f2b07666bf.png)
