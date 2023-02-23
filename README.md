# Docker Common Images
docker-compose.yml files for common needs

## Usage
```bash
# replace FILE NAME with the specific .yml file
docker compose --file "FILE_NAME" up
```
For example to launch a redis container
```bash
docker compose --file "docker-compose.redis.yml" up
```

## Containers
[redis](https://hub.docker.com/_/redis)
