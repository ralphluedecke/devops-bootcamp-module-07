# debug commands

## docker logs
shows the logs of the container
```bash
docker logs <container ID>
```

## docker run with name
starts a container with a specific name
```bash
docker run -d -p 6001:6379 --name redis-older redis:8.4
```

## docker exec
gets the terminal of an active container
```bash
docker exec -it <container ID> /bin/bash
```
```bash
docker exec -it <container name> /bin/bash
```