# docker-flask-hello-world
Simplest flask app you can build with docker!

## Build...
```
docker build --tag hello-world-image .
```

## Run...
```
docker run -d -p 8001:8000 --name hello-world-container hello-world-image
```
