Start postgres container
docker-compose up --build

Start postgres container detached
docker-compose up --build -d

Stop containers
docker-compose stop

Stop and remove containers
docker-compose down

List containers
docker ps

Get detailed information about a container
docker inspect <container id>