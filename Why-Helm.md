# Kubernetes problem solved by Helm

## PROBLEMS
- Kubernetes resources are created using `kubectl`
- `kubectl` uses manifest files called YAML files
- These YAML files have to be manually created or edited
- This creates problems in deployment to Production
- Every env need different value which can lead to manual changes and hence mistakes
- There can be many resources which need changes like deployment, configmap, service etc..
- What if one of the YAML file of a resource has an error. This can lead to inconsistent state.
- Upgrading applications of thirdparty can be complicated as you need to manually merge your changes with the 3rd party changes everytime
- ALL OF ABOVE PROBLEMS CAN BE SOLVED BY HELM CHARTS


## RESOLUTION
- Helm provides `Templates` & `Values`
- `Values` allow you to reuse templates with different parameters
