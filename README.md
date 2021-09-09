# Kubernetes Manifests for Jenkins Deployment

Refer https://devopscube.com/setup-jenkins-on-kubernetes-cluster/ for step by step process to use these manifests.

Here I am using my custom build docker image (you can provide your own image or use the provided)
```
  dhakadb/jenkins-centos:1.0.1
```
## Note
- change provide-your-worker-node in volume.yaml
- change <JENKINS_PASS> in deployment.yaml to override the existing initial admin password.