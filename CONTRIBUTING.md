# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-pcf_1.6.1_amd64.rock docker-daemon:sdcore-pcf:1.6.1
docker run sdcore-pcf:1.6.1
```