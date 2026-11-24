# Calendar App ArgoCD application

## Installation

1.[Create a new Repository using this template (optional)](https://github.com/DRSchlaubi/hsfulda-argocd-demo/generate)
2. Create a new ArgoCD Application

- Application Name: `argocd-demo`
- Project name: `default`
- Sync Policy: Auto
- Auto create namespace: On
- Source:
    - Url: <your repo from step 1> or https://github.com/DRSchlaubi/hsfulda-gitops-demo.git
    - Path: `calendar-argo`
