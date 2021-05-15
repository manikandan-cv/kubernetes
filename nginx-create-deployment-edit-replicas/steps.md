### Use Imperative command to create deployment

> kubectl create deployment my-ngix-deployment --image=nginx --replicas=1

### Use describe command to get the deployment details as yaml

> kubectl get deployments my-ngix-deployment -o yaml

### Remove optional properties in the yaml file & Change the name and labels in the yaml file 

### Use `kubectl create` command with the yaml file 

> kubectl create -f nginx-deployments.yaml

### change the replica set and re-apply the deployment

> kubectl apply -f nginx-deployments.yaml
