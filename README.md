# K8s-notes
Kubernetes deep-dive notes

## K8s Overview

![k1](https://user-images.githubusercontent.com/41537302/118336284-34f61980-b4c6-11eb-8954-72c9a41e7060.png)

![k2](https://user-images.githubusercontent.com/41537302/118336285-36bfdd00-b4c6-11eb-9cb2-23395b2a15a0.png)

## K8s API

It is declarative where we give the cluster YAML files and K8s will get it as a record of intent and update the desired state as the YAML configuration. The current state will be updated to match the desired state.

There are API groups defined in the API including Authorization, Apps etc.

## K8s Objects

### Pod 
- Contains one or more containers
- Atomic unit of scheduling
- Object on the cluster
- Defined in the v1 API group

### Deployment
- Object on the cluster
- Defined in the apps/v1 API group
- Make pods scalable, rolling updates
