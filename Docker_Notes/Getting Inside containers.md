# Getting a Shell inside Containers

*docker container run -it* - start new container interactively

*docker container exec -it* - run additional command in existing container 

Examples: 

 * *docker run -it --name proxy nginx bash* - gives you a terminal inside the running container 

 * *docker container exec -it mysql bash* - gets you a shell inside a running container 




