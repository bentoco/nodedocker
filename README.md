## First you must install docker and docker-compose and configure according documentation

 Install dependencies 
### `npm install express`
### `npm install nodemon`

 Sign in docker DockerID/Password
### `docker login`

 Docker container
### `docker build -t bentoco/nodedocker .`

 Run application without compose
### `docker run -p 3000:3000 -d bentoco/nodedocker`

 Run application with Docker Compose
### `docker-compose up`