# GitOps Deployment Example

Example of using OpenShift Pipelines and OpenShift GitOps to deploy a workload to OpenShift.

## Prerequisites
1. tkn and oc CLIs
```
wget https://mirror.openshift.com/pub/openshift-v4/clients/pipeline/0.21.0/tkn-linux-amd64-0.21.0.tar.gz
```

## Install
```
oc new-project
oc create -f git-clone-task.yaml
```
