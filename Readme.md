# KUBERNETES BASICS

## What is Kubernetes?

Kubernetes is a portable, extensible, open-source platform for managing containerized workloads and services—with a framework to run distributed systems resiliently. It takes care of your scaling requirements, failover, deployment patterns, scaling, load balancing, logging, and monitoring, much like PaaS offerings. However, it operates at the container level rather than at the hardware level.


## How Does Kubernetes Work?

Kubernetes works as a “container orchestration system” that manages the lifecycle of containerized applications and automates the deployment of several containers. Containers running the same applications are usually grouped together into Pods. There is a dedicated container orchestrator which supervises these groups and ensures that they operate correctly.


## Features of Kubernetes

### 1. Portable and Open-Sourced 
As an open-source platform, Kubernetes can run containers on any number of public clouds, virtual machines, or infrastructures. Its compatibility with most platforms makes it highly flexible and usable.

### 2. Programming Language and Framework Support 
Kubernetes supports most programming languages and frameworks.

### 3. Automatic Resource Bin Packing 
The application is packaged, and the containers scheduled based on available resources, allowing optimal utilization of unused resources. As Kubernetes enables you to specify the CPU and RAM needs of each container, the containers can be slotted to increase compute efficiency and ultimately lowers costs.  

### 4. Container Deployment Control 
Kubernetes allows complete control over the number of containers you want with deployment and keeps those containers ready with a rollout. Thus, you can automate Kubernetes to create new containers, remove existing containers, or adopt all of their resources to a new container. 

### 5. Persistent Storage Support 
Kubernetes workflow includes support for Amazon Web Services EBS, Google Cloud Platform persistent disks, and other storage.

### 6. Workload Support 
Kubernetes supports a variety of workloads: stateless, stateful, data-processing. 

### 7. Secure Configuration Management 
You can store and manage user information such as passwords and SSH keys, deploy secrets and application configuration without rebuilding your container images, and do all of this without exposing secrets in your stack configuration.

### 8. Service Discovery and Load Balancing 
Kubernetes can expose a container using the DNS or IP address. For high traffic to a container, it can automatically balance the loads into the pods and distribute the network traffic for the stable deployment of software. 

This supports the distribution of load and auto-balancing of resources instantly during incidental traffic or batch processing. 

### 9. Storage Orchestration 
You can automatically mount a storage system or orchestrate containers on multiple hosts.

### 10. Health Checks and Self-healing 
It checks the health of nodes and containers to ensure than an application doesn’t fail. In case of a pod crash or an error, Kubernetes automatically restarts containers that fail, replaces or kills containers that don’t match user-defined health checks, and doesn’t make them available to clients until they are client-ready.




