## Example wordpress using docker compose



### First Run

Run from the repo root

```shell
chmod +x init.sh && ./init.sh # not strictly necessary (docker compose should create folders by itself) 
docker compose up
```

### Commands
```shell
docker compose up                   # run all containers
docker compose up -d                # run all containers in daemon (background)
docker compose down                 # stop and remove all containers
docker compose stop                 # stop all containers
docker logs -f <container_name>     # follow logs of specific container
docker stats			    # check stats of running containers
docker ps			    # check running containers (add -a to also see stopped containers)
docker images			    # check locally available docker images
```
