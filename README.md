# pg-compose

This repo contains compose file for running postgres with pgAdmin and psql

## Getting started

1. Install docker

    ```
    sudo curl -sSL https://get.docker.com/ | sh && sudo groupadd docker 2>/dev/null && sudo gpasswd -a ${USER} docker && sudo service docker restart
    ```

1. [Install docker-compose](https://github.com/docker/compose/releases)

1. Run postgres and pgAdmin

    ```
    docker-compose up
    ```

1. Navigate to `localhost:5050`

1. Run psql

    ```
    docker-compose run --rm psql
    ```
