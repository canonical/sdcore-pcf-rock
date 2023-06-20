# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-pcf_1.3_amd64.rock docker-daemon:sdcore-pcf:1.3
docker run sdcore-pcf:1.3
```