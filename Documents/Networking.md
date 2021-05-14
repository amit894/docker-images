# docker-networking

## Types of Network

- `Bridge Network` : Isolated Containers which don't need to communicate with each other. Network isolation with host exists
- `Host Network` : Isolated Containers which don't need to communicate with each other. Network isolation with host removed.
- `Overlay Network` : Overlay networks connect multiple Docker daemons together and enable swarm services to communicate with each other.


## Docker Networking Commands
- `docker network ls` List all Available docker networks
- `docker network inspect` List details about given type of network and containers attached to it.
- `docker network connect <vnet-name> <container-name>` Connects a docker to a running network
- `docker network disconnect <vnet-name> <container-name>` Removes a docker from a running network
- `docker network create -d <network-type> <network-name>` Creates a VNET with a particular type of bridge,host,overlay nework settings
