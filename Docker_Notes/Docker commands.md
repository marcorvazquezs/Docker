# Docker command options 

## Commands to start, list, remove containers

```bash
# pull images down from dockerhub
docker pull

# lists running containers 
docker container ls

# publishes local host's port 80 to port 80 of container
docker container run --publish 80:80

# -d runs container in "detached" mode so it runs in background.
docker container run --d 

#  assigns a name to container instead of the randomly created name 
docker container run --name

# -f forces removal of running container
docker container rm -f  
```

## Commands to inspect containers 
```bash
# process list in one container
docker container top 

# details of one container config 
docker container inspect 

# performance stats for all containers
docker container stats 
```