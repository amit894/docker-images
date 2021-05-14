# docker-images
Repo's for Learning Docker

## Docker Installation

- `brew cask install docker`
- `docker --version`


## Basic Docker Commands

- `docker pull <imageName>` - Pulls images from container registry
- `docker push <imageName>` - Push images to container registry
- `docker images` - List all Local images
- `docker cp foo.txt <container-name:/location>` - Copies files to a running docker image
- `docker ps` - List all running containers
- `docker ps -a` - List all containers states
- `docker build -t <tag-name> .` - Builds a docker image
- `docker run --name <container-name> -d -p host-port:container-port <image-name>` - Runs a container in deamon mode
- `docker stop <container-id>` - Stops a running container in demon mode
- `docker kill <container-id>` - Kills a running container in demon mode
- `docker start <container-id>` - Starts a stopped container in demon mode
- `docker rm <container-id>` - Removes a stopped container
- `docker image rm <image-id>` - Removes an image
-  `docker container ls`  - List all running containers
