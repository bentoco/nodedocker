## First you must install docker and docker-compose and configure according documentation

## Dependencies 
```bash
$ npm install express
```
```bash
$ npm install nodemon
```

## Sign in docker DockerID/Password
```bash
$ docker login
```

## Docker container
```bash
$ docker build -t bentoco/nodedocker .
```

## Run application without docker-compose
```bash
$ docker run -p 3000:3000 -d bentoco/nodedocker
```

## Run application with docker-compose
```bash
$ docker-compose up
```


