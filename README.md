# GitOps with ArgoCD & Kubernetes

## Project Goal
This project demonstrates that I can set up a production-like Kubernetes environment with GitOps.  
- No manual `kubectl apply`  
- Git as the single source of truth  
- Automatic deployment on code changes  
- Fully observable and rollback-capable system

## Technologies Used
| Technology | Purpose |
|------------|---------|
| Kubernetes | Container orchestration |
| ArgoCD | GitOps controller |
| Helm | Kubernetes package manager |
| GitHub | Source of truth |
| kind | Local Kubernetes cluster |

## Architecture
- GitHub repository contains only deployment definitions (Helm chart)
- ArgoCD monitors GitHub repo
- Any change in GitHub triggers automatic cluster update

## Demonstrated Skills
- GitOps methodology
- ArgoCD application management
- Helm chart development
- Kubernetes declarative deployments
- Automated sync & rollback
