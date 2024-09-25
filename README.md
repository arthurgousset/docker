## Docker (Cheat Sheet)

> [!NOTE]  
> This is a cheat sheet on Docker (mostly notes-to-self). It is incomplete by default.

### Build Docker images locally

```sh
docker-compose build
```
### Run Docker images locally

```sh
docker-compose up
```
### List containers that are running

```sh
docker ps
```

### Execute shell command inside container

```sh
docker exec -it <container_name> mongosh
```
