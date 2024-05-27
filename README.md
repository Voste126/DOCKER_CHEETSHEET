# DOCKER_CHEETSHEET

a comprehensive docker commands

# Docker Cheat Sheet

| Command                                      | Description                                                                                       |
|----------------------------------------------|---------------------------------------------------------------------------------------------------|
| `docker --version`                           | Display the Docker version installed.                                                             |
| `docker info`                                | Display system-wide information.                                                                  |
| `docker help`                                | Get help on Docker commands.                                                                      |
| `docker pull <image>`                        | Download an image from a registry.                                                                |
| `docker images`                              | List all Docker images on the local system.                                                       |
| `docker ps`                                  | List all running containers.                                                                      |
| `docker ps -a`                               | List all containers, including stopped ones.                                                      |
| `docker run <image>`                         | Run a container from an image.                                                                    |
| `docker run -it <image> /bin/bash`           | Run a container in interactive mode with a bash shell.                                            |
| `docker exec -it <container> /bin/bash`      | Run a command in a running container.                                                             |
| `docker stop <container>`                    | Stop a running container.                                                                         |
| `docker start <container>`                   | Start a stopped container.                                                                        |
| `docker restart <container>`                 | Restart a running container.                                                                      |
| `docker rm <container>`                      | Remove a stopped container.                                                                       |
| `docker rmi <image>`                         | Remove an image.                                                                                  |
| `docker build -t <name> .`                   | Build an image from a Dockerfile in the current directory.                                         |
| `docker commit <container> <new_image>`      | Create a new image from a container's changes.                                                    |
| `docker tag <image> <new_image>`             | Tag an image to a new name.                                                                       |
| `docker login`                               | Log in to a Docker registry.                                                                      |
| `docker push <image>`                        | Push an image to a registry.                                                                      |
| `docker network ls`                          | List all Docker networks.                                                                         |
| `docker network create <network>`            | Create a new Docker network.                                                                      |
| `docker network connect <network> <container>` | Connect a container to a network.                                                                |
| `docker network disconnect <network> <container>` | Disconnect a container from a network.                                                           |
| `docker network inspect <network>`           | Display detailed information on a network.                                                        |
| `docker network rm <network>`                | Remove a Docker network.                                                                          |
| `docker volume ls`                           | List all Docker volumes.                                                                          |
| `docker volume create <volume>`              | Create a new Docker volume.                                                                       |
| `docker volume rm <volume>`                  | Remove a Docker volume.                                                                           |
| `docker inspect <container|image|network|volume>` | Display detailed information on a container, image, network, or volume.                          |
| `docker logs <container>`                    | Fetch the logs of a container.                                                                    |
| `docker top <container>`                     | Display the running processes of a container.                                                     |
| `docker stats <container>`                   | Display a live stream of resource usage statistics for containers.                                |
| `docker cp <container>:<path> <host_path>`   | Copy files/folders between a container and the local filesystem.                                  |
| `docker-compose up`                          | Create and start containers using Docker Compose.                                                |
| `docker-compose down`                        | Stop and remove containers, networks, images, and volumes created by `docker-compose up`.         |
| `docker-compose build`                       | Build or rebuild services defined in a Docker Compose file.                                       |
| `docker-compose ps`                          | List containers managed by Docker Compose.                                                        |
| `docker-compose logs`                        | View output from containers managed by Docker Compose.                                            |
| `docker-compose exec <service> <command>`    | Run a command in a running service managed by Docker Compose.                                     |
| `docker-compose stop`                        | Stop running containers without removing them.                                                    |
| `docker-compose rm`                          | Remove stopped containers.                                                                        |
| `docker network prune`                       | Remove all unused networks.                                                                       |
| `docker run --network <network> <image>`     | Run a container with a specific network.                                                          |
| `docker run --dns <dns_server> <image>`      | Run a container with a custom DNS server.                                                         |
| `docker run --network-alias <alias> <image>` | Run a container with a network alias.                                                             |
| `docker run -p <host_port>:<container_port> <image>` | Map a host port to a container port.                                                           |
| `docker network create --driver bridge <network>` | Create a user-defined bridge network.                                                          |
| `docker network create --driver overlay <network>` | Create a user-defined overlay network.                                                         |
| `docker network create --subnet <subnet> <network>` | Create a network with a specific subnet.                                                      |
| `docker network create --ip-range <ip-range> <network>` | Create a network with a specific IP range.                                                   |
| `docker network create --gateway <gateway> <network>` | Create a network with a specific gateway.                                                     |
| `docker run --hostname <hostname> <image>`   | Run a container with a specific hostname.                                                        |

Feel free to customize this table according to your specific needs and add any additional commands you find useful.
