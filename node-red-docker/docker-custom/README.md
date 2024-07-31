# Build the ReEnvision Docker Image

## Git Clone


## Run Build Script

```
./docker-debian.sh
```

## Start Container
```
docker run -it -p 1880:1880 -v node_red_data:/data --name myNRtest testing:node-red-build
```