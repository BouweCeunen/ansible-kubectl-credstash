# ansible-kubectl-credstash-argo
Dockerfile with ansible, kubectl, credstash and argo in order to deploy on Kubernetes.

[![DockerHub Badge](https://dockeri.co/image/bouwe/ansible-kubectl-credstash-argo)](https://hub.docker.com/r/bouwe/ansible-kubectl-credstash-argo)

## usage
Kubectl, ansible, credstash and argo can be executed from within a pod on your Kubernetes cluster. Don't forget to assign credstash policy to your node role in AWS IAM. If RBAC is enabled a cluster role should be assigned and attached to the service account of your deployment.