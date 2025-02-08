```sh
helm repo add argo https://argoproj.github.io/argo-helm
helm install argocd argo/argo-cd -f values.yaml
helm upgrade argocd argo/argo-cd -f values.yaml
```