# Run BMM via podman

```bash
sudo podman play kube ./bmm-deployment.yaml
sudo podman pod ps
sudo podman container logs -f <container-id>
sudo podman pod rm bmm-deployment --force
```
