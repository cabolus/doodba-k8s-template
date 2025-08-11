# Proyecto Odoo en Kubernetes
Generado desde `doodba-k8s-template`. Incluye:
- Build de imagen con Doodba (solo build)
- Despliegue en Kubernetes con Helm (web + cron + service + ingress)
- CI/CD con GitHub Actions

## Pasos rápidos
1) Configura secrets en GitHub: REGISTRY, REGISTRY_USER, REGISTRY_PASSWORD, KUBE_CONFIG  
2) Ejecuta `scripts/bootstrap-k8s.sh`  
3) Haz push a `main` para disparar build + deploy
