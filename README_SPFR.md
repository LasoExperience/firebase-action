# Docker Build

on ARM
 
```shell
docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 -t spfr/firebase-action:latest --push . 
```

On x86

```shell
docker build -t spfr/firebase-action:latest --push . 
```
