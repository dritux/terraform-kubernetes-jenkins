# Terraform - Kubernetes - Jenkins

This module installs jenkins in your kubernetes cluster through the kubernetes deployment.

## Requirement

Kubernetes [provider](https://www.terraform.io/docs/providers/kubernetes/index.html) set up in your terraform configs.

### Example Usage
```
module "jenkins" {
  source            = "dritux/jenkins/kubernetes"
  version           = "1.0.0"
  create_namespace  = true
}
```
