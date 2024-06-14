# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-pcf_1.4.2_amd64.rock docker-daemon:sdcore-pcf:1.4.2
docker run sdcore-pcf:1.4.2
```