[README.md](https://github.com/user-attachments/files/23415582/README.md)
# env-repo

Kubernetes manifests and CD pipeline.

- `k8s/deployment.yaml` manifest is updated by CI with the new image tag.
- CD trigger applies the manifest to the GKE cluster.
