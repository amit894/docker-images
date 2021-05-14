# docker-images
Repo's for Learning Docker

##Docker Installation

- `brew cask install docker`
- `docker --version`


##Basic Docker Commands

- `docker pull <imageName>`
- `docker push <imageName>`
- `docker images`
- `docker cp foo.txt <container-name:/location>`
- `docker ps`
- `docker build -t <tag-name> .`
- `docker run --name <container-name> -d -p host-port:container-port <image-name>`
- `docker stop <container-id>`
- `docker kill <container-id>`
- `docker rm <container-id>`
- `docker image rm <image-id>`
-  `docker container ls`
