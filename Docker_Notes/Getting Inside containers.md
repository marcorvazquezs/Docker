# Getting a Shell inside Containers

*docker container run -it* - start new container interactively

*docker container exec -it* - run additional command in existing container 

Example: 

 * *docker run -it --name proxy nginx bash* - gives you a terminal inside the running container 