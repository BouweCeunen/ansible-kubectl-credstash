# ansible-kubectl-credstash
Dockerfile with ansible, kubectl and credstash in order to deploy on Kubernetes.

[![DockerHub Badge](https://dockeri.co/image/bouwe/ansible-kubectl-credstash)](https://hub.docker.com/r/bouwe/ansible-kubectl-credstash)

## usage
Kubectl, ansible and credstash can be executed from within a pod on your Kubernetes cluster. Don't forget to assign credstash policy to your node role in AWS IAM. If RBAC is enabled a cluster role should be assigned and attached to the service account of your deployment.