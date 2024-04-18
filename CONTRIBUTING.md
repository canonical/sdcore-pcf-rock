# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:sdcore-pcf_1.4.1_amd64.rock docker-daemon:sdcore-pcf:1.4.1
docker run sdcore-pcf:1.4.1
```