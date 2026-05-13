```
ansible-builder build -v3 --build-arg ANSIBLE_GALAXY_CLI_COLLECTION_OPTS="--pre -v" --tag quay.io/sagpaul/meraki-ops:latest --container-runtime podman
podman login -u='sagpaul' -p='v---------------------------------------------' quay.io
podman push localhost/clus-ee quay.io/sagpaul/clus-ee:v1
```
