# docker-flask-hello-world
Simplest flask app you can build with docker!

## Build...
From the directory containing this `Dockerfile` run:
```
docker build --tag image-name .
```

## Run...
```
docker run -d -p 8001:8000 --name container-name image-name
```
