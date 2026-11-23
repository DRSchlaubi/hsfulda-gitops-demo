# Calendar App ArgoCD application

## Installation

1. Create a new ArgoCD Application

- Application Name: `argocd-demo`
- Project name: `default`
- Sync Policy: Auto
- Auto create namespace: On
- Source:
    - Url: https://github.com/DRSchlaubi/hsfulda-gitops-demo.git
    - Path: `calendar-argo`
