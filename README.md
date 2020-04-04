# ELK + Nginx on Docker

### Build & Run

- *>docker-compose up* --build : build docker images and containers and run containers
- *>docker-compose up -d*  : docker compose for detached mode
- *>docker-compose stop* : stop the dockerized services
- *>docker container logs --container-id--* : view the logs of a docker container

### Docker Commands

- *>docker ps : get the name of the existing container
- *>docker exec -it --container name-- sh : container shell
- *>docker-compose run --container name-- --command-- : run a command in container


URI for nginx : *http://localhost:8080*

## Getting Started

To run this stack, run the following command
```bash
docker-compose up
```
Then go to `http://localhost:5601` to see your data in Kibana

Default Kibana user information
- Username: elastic
- Password: changeme
