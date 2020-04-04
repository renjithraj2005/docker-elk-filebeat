### Docker 

- docker image build -t nginx-app:latest .


### Build & Run

- *>docker-compose up* --build : build docker images and containers and run containers
- *>docker-compose up -d*  : docker compose for detached mode
- *>docker-compose stop* : stop the dockerized services
- *>docker container logs <container-id>* : view the logs of a docker container
- Each maven module has a Dockerfile.

URI for nginx : *http://localhost:8080*