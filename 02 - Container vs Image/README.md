# Container vs Image

## docker images
- contains layers of images
- mostly linux base image - small size
- application image on top

## install docker
- see ubuntu install description

## postgresql example
```bash
docker run -e POSTGRES_PASSWORD=mysecretpass postgres:17.10
```
check with "docker ps" that container is running

## what is the image
- the actual package
- artifact that can be moved around

## what is the container
- running instance of an image
- starts the application
- container environment is created

## postgresql 2cnd example
```bash
docker run -e POSTGRES_PASSWORD=mysecretpass postgres:18.4
```
- see that some layers are already there and will not be pulled again
- check with "docker ps" that both containers are started