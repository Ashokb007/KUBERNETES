# Kubectl Commands

## Pods and Container Commands

### Kubectl get pods
Lists all current pods

### Kubectl describe pod<name>
Describes pod names

### Kubectl get rc
Lists all replication controllers

### Kubectl get cvc
Lists services

### Kubectl delete pod<name>
Deletes a pod

### Kubectl get nodes -w
Watches nodes continuously

## Debugging Commands

### Kubectl exec<service><commands>[-c< $container>]
Executes the command on service by choosing a container

### Kubectl logs -f<name>>[-c< $container>]
Gets logs from the service for a container

### Kubectl top node
Shows metrics for a node

### Kubectl top pod
Shows metrics for a pod

### Kubectl cluster-info
To get cluster-related information

### Kubectl describe node<node>
To get information about a node

##  Quick Commands


### Kubectl run<name> — image=<image-name>
Launching a pod with a name and image.

### Kubectl create -f <manifest.yaml>
To create a service detailed in <manifest.yaml>

### Kubectl scale –replicas=<count>rc<name>
To scale the replication counter, counting the number of instances.

### Kubectl drain<n>– delete-local-data–force–ignore-daemonset
Stopping all pods in <n>

### Kubectl create namespace <namespace>
To create a namespace.


# ENJOY THE LEARNING...😊😊







