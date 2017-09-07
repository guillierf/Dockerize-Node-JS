# Dockerize-Node-JS

## Example taken from:
https://nodejs.org/en/docs/guides/nodejs-docker-webapp/

## Procedure

Build the docker image:
```
$ docker build -t <your username>/node-web-app .
```

Run a container using the image:
```
$ docker run -p 49160:8080 -d <your username>/node-web-app
```

## Test

```
$ curl localhost:49160
```

