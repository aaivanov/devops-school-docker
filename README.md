git clone git@github.com:aaivanov/devops-school-docker.git

cd devops-school-docker

git submodule update --init --recursive







Homework1:

dockerfile - Dockerfile_frontend

docker build -t frontend:latest -f Dockerfile_frontend .

docker run -it --rm -p 3000:3000 frontend:latest

Ctrl+C for stop and exit from docker

Homework2:

dockerfile - Dockerfile_lib_catalog

docker-compose -f docker-compose_lib_catalog.yml up -d

for stop dockers:

docker-compose -f docker-compose_lib_catalog.yml down  

Homework3:

docker-compose -f docker-compose.yml up -d

for stop dockers:

docker-compose -f docker-compose.yml down 
