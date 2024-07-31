# Build the ReEnvision Docker Image

## Git Clone
```
git@github.com:ReEnvision-AI/reenvision-docker.git
cd reenvision-docker/node-red-docker/docker-custom
```

## Run Build Script

```
./docker-debian.sh
```

## Start Container
```
docker run -it -p 1880:1880 -v node_red_data:/data --name myNRtest testing:node-red-build
```