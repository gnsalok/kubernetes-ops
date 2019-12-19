# Kubernetes Security
This page is here to describe security challenages and possible solutions to various security concerns in a 
Kubernetes deployment.

## Control plane

![the stack](/docs/kubernetes-security/images/kubernetes-controle-plane.png)

### 1
All pieces communicates with the Kubernetes API via the same interface through a RESTful API.

## Example application

![the stack](/docs/kubernetes-security/images/example-application.png)

### 1
This is the only external entry point into the Kubernetes cluster from the internet.