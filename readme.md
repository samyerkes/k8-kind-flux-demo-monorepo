# Sample GitOps K8 Cluster

The following is a sample repo to install cluster configuration into Kubernetes via Flux CD. Installing it into a cluster will apply:
* a namespace (my-namespace)
* a deployment with 3 replicas (echo-deployment)
* a service (echo-service)
* an ingress (echo-ingress)
