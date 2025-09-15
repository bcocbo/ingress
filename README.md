# Ambiente Pruebas GitOps con Istio Ingress

## Setup
1. Bootstrap EKS y ArgoCD (ver instrucciones).
2. Configura DNS: CNAME `apps.pocarqnube.com` → Istio LB hostname.
3. En ArgoCD UI: Crea root-app apuntando a este repo (path: manifests/).
4. Mergea PRs: ArgoCD sync automático.


## Pruebas
- https://apps.pocarqnube.com/ → Página rutas.
- /argocd → ArgoCD UI.
- /backstage → Backstage.
