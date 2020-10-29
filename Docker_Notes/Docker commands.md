# Docker command options 

## Commands to start, list, remove containers

*docker pull* - pull images down from dockerhub

*docker container ls* = lists running containers 

*docker container run --publish 80:80* = publishes local host's port 80 to port 80 of container 

*docker container run --d* = -d runs container in "detached" mode so it runs in background. 

*docker container run --name* = assigns a name to container instead of the randomly created name 

*docker container rm -f* = forces removal of running container 


## Commands to inspect containers 

*docker container top* - process list in one container

*docker container inspect* - details of one container config 

*docker container stats* - performance stats for all containers