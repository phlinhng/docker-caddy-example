# docker-caddy-example
An example demostration of deploying caddy and service (using `react` as example) with `docker-compose`.

## Install `docker` and `docker compose`
```properties
sudo apt-get update
sudo apt-get upgrade
sudo apt install curl
sudo apt install docker.io
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
## build and run containers
```properties
docker-compose up --build
```

## test result
> http://localhost:8080/
A default react web page should show up.