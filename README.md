# Skopeo container

The Skopeo binary in a CentOS container. Simple.

## Build

Clone the upstream repo and `make` the binary:

```
git clone git@github.com:projectatomic/skopeo.git
make binary
```

This will produce the `skopeo` binary.

Now build the container:

`docker build -t ${USER}/skopeo:latest -f Dockerfile.simple .`
