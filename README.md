## Example wordpress using docker compose



### First Run

Run from the repo root

```shell
chmod +x init.sh 
./init.sh 
docker compose up
```

### Commands
```shell
docker compose up                   # run all containers
docker compose up -d                # run all containers in daemon (background)
docker compose down                 # stop and remove all containers
docker compose stop                 # stop all contains
docker logs -f <container_name>     # follow logs of specific container
```
