# Docker Networking 

### Defaults 

* Each container connected to a private virtual network "bridge" 
* Each virtual network routes through NAT firewall on host IP 
* All containers on a virtual network can talk to each other without **-p**
* **Best Practice** is to create a new virtual network for each app

**Get Docker container IP Address**
```docker
docker container inspect --format '{{ .NetworkSettings.IPAddress }}' container_name
```

### CLI Management Commands 
```bash 
# Show networks 
docker network ls

# Inspect a network 
docker network inspect

# Create a network 
docker network create --driver

# Attach a network to container 
docker network connect 

# Detach a network from container 
docker network disconnect
```

