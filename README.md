# Web Stack
Docker compose: PHP + Nginx + Redis + Nodejs + MySQL + phpMyAdmin
## Use
```bash
# copy .env
cp .env.docker .env

# build
docker-compose up --build

# commands: start, restart, stop
docker-compose [command]

# Stop and remove containers, networks, images, and volumes
docker-compose down --rmi=all
```
