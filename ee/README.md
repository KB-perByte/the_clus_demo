```
ansible-builder build --tag quay.io/sagpaul/clus-ee:latest --container-runtime podman
podman login -u='sagpaul' -p='v---------------------------------------------' quay.io
podman push quay.io/sagpaul/clus-ee:latest
```
