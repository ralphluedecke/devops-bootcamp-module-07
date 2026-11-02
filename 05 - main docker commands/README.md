# main docker commands

## overview
- docker pull
- docker run
- docker start
- docker stop
- docker ps
- docker exec -it
- docker logs

## container has...
- file system (virtual file system inside)
- environment configs
- application image
- port

## docker pull
pulls an image
```bash
docker pull redis
```

## docker images
shows all images on local with their properties
```bash
docker images
```

## docker run
starts a new container
```bash
docker run redis
```

## docker ps
shows a list of running containers
```bash
docker ps
```

## docker ps -a
shows the list of running and stopped containers
```bash
docker ps -a
```

## docker run detached
starts a new container in detached mode
```bash
docker run -d redis
```

## docker stop
stops the container
```bash
docker stop <ID of container>
```

## docker start
starts the container
```bash
docker start <ID of container>
```

## docker run with port binding
- starts a new container with a specified port
- first port is the port of the host machine
- second port is the port inside the container
```bash
docker run -p 6000:6379 -d redis
```