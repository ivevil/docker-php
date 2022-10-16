# PHP Website using Docker Containers with PHP Apache and MySQL
In order to run a containerized PHP development enviroment we will use Docker hub images.

## What will happen when you run the composer up?
- Setup and run of a local PHP Apache server instance.
- Setup of a MySQL database.

## Prerequisites
Installed Docker and basic understanding of running docker-compose commands. You will also need to run a query on database later in order to start fully the whole project on your local machine. That would be added later, for now you can see "Hello world" after running the project and openning http://localhost:8000/

## Notes before you start
After you pull the code from this repository, please check if you want to keep the same parameters for username/password. Also, please be aware if you are running any other docker containers it could cause you trouble with running this one. It would be the best to stop all other containers and then run this one. 

## Magic command to install everything and start the containers
`docker-compose up -d`