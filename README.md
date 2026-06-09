# nutricore-infra

Infraestructura completa del proyecto NutriCore.
Dockerfiles, Kubernetes manifests y pipelines CI/CD con Jenkins.

## Estructura
- `docker/`   — Dockerfiles de frontend y backend
- `k8s/`      — Manifests de Kubernetes por entorno (dev, staging, prod)
- `jenkins/`  — Jenkinsfiles del pipeline CI/CD
- `scripts/`  — Scripts de configuración del entorno local

## Entornos
| Entorno | Herramienta | Namespace K8s |
|---------|-------------|---------------|
| Development | Docker Compose | nutricore-dev |
| Staging | minikube | nutricore-stg |
| Production | minikube | nutricore-prod |

## Parte del proyecto NutriCore
- [nutricore-frontend](https://github.com/Alberto-SGT/nutricore-frontend)
- [nutricore-backend](https://github.com/Alberto-SGT/nutricore-backend)
