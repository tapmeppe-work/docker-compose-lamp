# LAMP stack built with Docker Compose

![Landing Page](https://user-images.githubusercontent.com/43859895/141092846-905eae39-0169-4fd7-911f-9ff32c48b7e8.png)

A basic LAMP stack environment built using Docker Compose. It consists of the following:
- Apache
- PHP
  - WordPress v6.4.3
- MySQL
- phpMyAdmin
- Redis

For more information see the [source repository](https://github.com/sprintcube/docker-compose-lamp).<br>
Additionally an [alternative approach](https://medium.com/@mikez_dg/how-to-set-up-a-simple-lamp-server-with-docker-images-in-2023-9b0e24476ec6).


## Installation
- Clone this repository on your local computer
- configure .env as needed
- Run the `docker compose up -d`.

```shell
git clone https://github.com/tapmeppe-work/dockeroolamp-wordpressit.git
cd __PATH__/__TO__/__CONTAINER__/
cp .env.template .env
docker compose up -d
```


## phpMyAdmin
phpMyAdmin is configured to run on port 7503. Use following default credentials.

- URL:			http://localhost:7503/  
- Username:	root  
- Password:	qw3rtzu10p

